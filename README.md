# Philosophers ππΌββοΈππΎββοΈπ
## I never thought philosophy would be so deadly

![philo](https://user-images.githubusercontent.com/100228348/219851895-e5b85530-22d0-4a42-8db2-5238d165b5c4.gif)

## About
The goal of this project was to learn to avoid deadlock and race conditions when creating multithreaded applications.

## Here are the things you need to know if you want to succeed this assignment:

β’ One or more philosophers sit at a round table. 
There is a large bowl of spaghetti in the middle of the table. π

β’ The philosophers alternatively eat, think, or sleep.
While they are eating, they are not thinking nor sleeping; π½
while thinking, they are not eating nor sleeping; π€
and, of course, while sleeping, they are not eating nor thinking. π€

β’ There are also forks on the table. There are as many forks as philosophers.

β’ Because serving and eating spaghetti with only one fork is very inconvenient, a philosopher takes their right and their left forks to eat, one in each hand.

β’ When a philosopher has finished eating, they put their forks back on the table and start sleeping. Once awake, they start thinking again. The simulation stops when a philosopher dies of starvation.

β’ Every philosopher needs to eat and should never starve.

β’ Philosophers donβt speak with each other. π

β’ Philosophers donβt know if another philosopher is about to die. π

β’ No need to say that philosophers should avoid dying!

### Rules
The program takes the following arguments:

`./philo <number_of_philosophers> <time_to_die> <time_to_eat> <time_to_sleep> [number_of_times_each_philosopher_must_eat]`

π `number_of_philosophers`: The number of philosophers and also the number
of forks.

π `time_to_die` (in milliseconds): If a philosopher didnβt start eating time_to_die
milliseconds since the beginning of their last meal or the beginning of the simulation, they die.

π `time_to_eat` (in milliseconds): The time it takes for a philosopher to eat.
During that time, they will need to hold two forks.

π€ `time_to_sleep` (in milliseconds): The time a philosopher will spend sleeping.

π½ `number_of_times_each_philosopher_must_eat` (optional argument): If all philosophers have eaten at least `number_of_times_each_philosopher_must_eat` times, the simulation stops. If not specified, the simulation stops when a philosopher dies.

## Installation
The program is compiled into a `philo` executable using ``make``.
Example  ``./philo 5 800 200 200 3``
 
