from timeit import default_timer as timer
import rebootPC
import copy_directory
import delete_directory
for x in range(0, 5):
    start = timer()
    rebootPC.main()
    end = timer()
    print(end - start)
for x in range(0, 5):
    start = timer()
    unzipFile.main()
    end = timer()
    print(end - start)

for x in range(0, 5):
    start = timer()
    copy_directory.main()
    end = timer()
    print(end - start
for x in range(0, 5):
    start = timer()
    delete_directory.main()
    end = timer()
    print(end - start)
