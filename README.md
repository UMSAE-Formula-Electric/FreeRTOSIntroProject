FreeRTOS Intro project for new members!

Some great FreeRTOS docs can be found at: https://www.freertos.org/Documentation/RTOS_book.html

If you have taken Operating Systems (or are eager to learn), read around the different mutexes, waits, and signals that you can use to reliably communicate between threads.

To complete this intro project, create three (3) tasks that turn on a GPIO at different times, and then wait for a signal. Create a new task that waits for all three GPIOs to be written to (hint: use xEventGroupSync!!), turns them all off, and signals the 3 worker tasks to continue again.
