# 3_4_2_posix_semaphore


``` sh
❯ gcc main.c
❯ ./a.out
count = 1, thread_num = 2, loop_cnt = 0
count = 2, thread_num = 1, loop_cnt = 0
count = 3, thread_num = 5, loop_cnt = 0
count = 1, thread_num = 3, loop_cnt = 0
count = 2, thread_num = 4, loop_cnt = 0
count = 3, thread_num = 6, loop_cnt = 0
count = 1, thread_num = 0, loop_cnt = 0
count = 2, thread_num = 7, loop_cnt = 0
count = 3, thread_num = 8, loop_cnt = 0
count = 1, thread_num = 9, loop_cnt = 0
count = 2, thread_num = 5, loop_cnt = 1
count = 3, thread_num = 1, loop_cnt = 1
count = 2, thread_num = 3, loop_cnt = 1
count = 2, thread_num = 2, loop_cnt = 1
count = 3, thread_num = 4, loop_cnt = 1
count = 1, thread_num = 6, loop_cnt = 1
count = 2, thread_num = 0, loop_cnt = 1
count = 3, thread_num = 7, loop_cnt = 1
count = 1, thread_num = 8, loop_cnt = 1
count = 2, thread_num = 9, loop_cnt = 1
count = 3, thread_num = 1, loop_cnt = 2
count = 2, thread_num = 5, loop_cnt = 2
count = 2, thread_num = 3, loop_cnt = 2
count = 3, thread_num = 2, loop_cnt = 2
count = 1, thread_num = 4, loop_cnt = 2
count = 2, thread_num = 6, loop_cnt = 2
count = 3, thread_num = 0, loop_cnt = 2
count = 1, thread_num = 8, loop_cnt = 2
count = 2, thread_num = 7, loop_cnt = 2
count = 3, thread_num = 9, loop_cnt = 2
count = 1, thread_num = 1, loop_cnt = 3
count = 2, thread_num = 5, loop_cnt = 3
count = 3, thread_num = 3, loop_cnt = 3
count = 1, thread_num = 2, loop_cnt = 3
count = 2, thread_num = 4, loop_cnt = 3
count = 3, thread_num = 6, loop_cnt = 3
count = 1, thread_num = 0, loop_cnt = 3
count = 2, thread_num = 8, loop_cnt = 3
count = 3, thread_num = 7, loop_cnt = 3
count = 1, thread_num = 9, loop_cnt = 3
count = 2, thread_num = 1, loop_cnt = 4
count = 3, thread_num = 3, loop_cnt = 4
count = 1, thread_num = 5, loop_cnt = 4
count = 3, thread_num = 4, loop_cnt = 4
count = 2, thread_num = 2, loop_cnt = 4
count = 1, thread_num = 6, loop_cnt = 4
count = 2, thread_num = 0, loop_cnt = 4
count = 3, thread_num = 8, loop_cnt = 4
count = 2, thread_num = 7, loop_cnt = 4
count = 2, thread_num = 9, loop_cnt = 4
count = 3, thread_num = 1, loop_cnt = 5
count = 1, thread_num = 3, loop_cnt = 5
count = 2, thread_num = 5, loop_cnt = 5
count = 3, thread_num = 4, loop_cnt = 5
count = 1, thread_num = 2, loop_cnt = 5
count = 3, thread_num = 0, loop_cnt = 5
count = 2, thread_num = 6, loop_cnt = 5
count = 1, thread_num = 8, loop_cnt = 5
count = 2, thread_num = 7, loop_cnt = 5
count = 3, thread_num = 9, loop_cnt = 5
count = 1, thread_num = 1, loop_cnt = 6
count = 2, thread_num = 3, loop_cnt = 6
count = 3, thread_num = 5, loop_cnt = 6
count = 1, thread_num = 4, loop_cnt = 6
count = 2, thread_num = 2, loop_cnt = 6
count = 3, thread_num = 0, loop_cnt = 6
count = 1, thread_num = 6, loop_cnt = 6
count = 2, thread_num = 8, loop_cnt = 6
count = 3, thread_num = 7, loop_cnt = 6
count = 1, thread_num = 9, loop_cnt = 6
count = 2, thread_num = 1, loop_cnt = 7
count = 3, thread_num = 3, loop_cnt = 7
count = 1, thread_num = 4, loop_cnt = 7
count = 2, thread_num = 5, loop_cnt = 7
count = 3, thread_num = 2, loop_cnt = 7
count = 1, thread_num = 0, loop_cnt = 7
count = 2, thread_num = 6, loop_cnt = 7
count = 3, thread_num = 8, loop_cnt = 7
count = 1, thread_num = 7, loop_cnt = 7
count = 3, thread_num = 1, loop_cnt = 8
count = 2, thread_num = 9, loop_cnt = 7
count = 1, thread_num = 3, loop_cnt = 8
count = 2, thread_num = 4, loop_cnt = 8
count = 3, thread_num = 5, loop_cnt = 8
count = 1, thread_num = 0, loop_cnt = 8
count = 2, thread_num = 2, loop_cnt = 8
count = 3, thread_num = 6, loop_cnt = 8
count = 1, thread_num = 8, loop_cnt = 8
count = 3, thread_num = 1, loop_cnt = 9
count = 2, thread_num = 7, loop_cnt = 8
count = 1, thread_num = 9, loop_cnt = 8
count = 2, thread_num = 3, loop_cnt = 9
count = 3, thread_num = 4, loop_cnt = 9
count = 1, thread_num = 5, loop_cnt = 9
count = 2, thread_num = 0, loop_cnt = 9
count = 3, thread_num = 2, loop_cnt = 9
count = 2, thread_num = 6, loop_cnt = 9
count = 2, thread_num = 8, loop_cnt = 9
count = 3, thread_num = 7, loop_cnt = 9
count = 1, thread_num = 9, loop_cnt = 9
❯ 
```
