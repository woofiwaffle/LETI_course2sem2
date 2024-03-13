<p align = "center">
  <img src = "https://img.shields.io/badge/Ubuntu-22.04_LTS-g?style=plastic&logo=Ubuntu&logoColor=black&labelColor=%23E95420&color=lightgrey" alt = "Linux Ubuntu version">
  <img src = "https://img.shields.io/badge/Compiler-g%2B%2B-g?style=plastic&labelColor=blue&color=lightgrey" alt = "Compiler">
</p>

# LETI Operating Systems

## About 
1. practical1 --- Creating and Destroying Threads
~~~
Display the value of the default “scheduling parameter” attribute for any of the threads, change its
value and illustrate the change in the attribute. Explain the essence of the attribute.
~~~
2. practical2 --- Synchronizing threads using unnamed semaphores
~~~ 
program 1 – without synchronization tools,
program 2 – sem_wait(),
program 3 – sem_timedwait().
~~~
3. practical3 --- Interaction of threads through unnamed pipes
~~~
Function 21

int getnetent_r(struct netent *restrict result_buf, char *restrict buf,
                size_t buflen, struct netent **restrict result, int *restrict h_errnop);
- get the netent structure,
select a field from the structure, for example, n_name, and transmit it
~~~
4. practical4 --- Creation and destruction of processes
~~~
Function 7

int execvpe(const char *file, char *const argv[], char *const envp[]).
~~~
5. practical5 --- Synchronizing processes using named semaphores
~~~
Function 7

1) epoll_create() – creating an epoll instance;
2) epoll_ctl() – instance management;
3) epoll_wait() – waiting for an event to occur.

The epoll instantiation function has the following prototype:
int epoll_create(int size);

The epoll instance control function has the following prototype:
int epoll_ctl(int epfd, int op, int fd, struct epoll_event *event);

epoll events are described by the following data structures:
struct epoll_event {
       uint32_t events;
       epoll_data_t data;
};
typedef union epoll_data {
       void *ptr;
       int fd;
       uint32_t u32;
       uint64_t u64;
} epoll_data_t;

The epoll_wait() function has the following prototype:
int epoll_wait(int epfd, struct epoll_event *events, int maxevents, int timeout);
~~~
6. practical6 ---
7. practical7 ---
8. practical8 ---

## Developer

*  [woofiwaffle](https://github.com/woofiwaffle)
