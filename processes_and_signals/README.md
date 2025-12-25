# 0-what-is-my-pid : Bash script that displays its own PID.

# 1-list_your_processes : Bash script that displays a list of currently running processes.

#    Requirements:

#       Must show all processes, for all users, including those which might not have a TTY
#       Display in a user-oriented format
#       Show process hierarchy

# 2-show_your_bash_id : Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.

#       Requirements:

#           You cannot use pgrep
#           The third line of your script must be # shellcheck disable=SC2009

# 3-show_your_bash_pid_made_easy : Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.

#       Requirements:

#           You cannot use ps

# 4-to_infinity_and_beyond : Bash script that displays To infinity and beyond indefinitely.

#       Requirements:

#           In between each iteration of the loop, add a sleep 2

# 5-dont_stop_me_now : Bash script that stops 4-to_infinity_and_beyond process.

#       Requirements:

#           You must use kill

# 6-stop_if_you_can : Bash script that stops 4-to_infinity_and_beyond process.

#       Requirements:

#           You cannot use kill or killall

# 7-highlander,67-stop_me_if_you_can : a Bash script that displays:

#       To infinity and beyond indefinitely
#       With a sleep 2 in between each iteration
#       I am invincible!!! when receiving a SIGTERM signal
#       Make a copy of your 6-stop_me_if_you_can script, name it 67-stop_me_if_you_can, that kills the 7-highlander process instead of the 4-to_infinity_and_beyond one.

# 8-beheaded_process : Bash script that kills the process 7-highlander.

# # manage_my_process : Bash script that:

# Indefinitely writes I am alive! to the file /tmp/my_process
# In between every I am alive! message, the program should pause for 2 seconds
# 11-manage_my_process :

# Bash (init) script 11-manage_my_process that manages manage_my_process. (both files need to be pushed to git)

# Requirements:

#       When passing the argument start:
#               Starts manage_my_process
#               Creates a file containing its PID in /var/run/my_process.pid
#               Displays manage_my_process started
#       When passing the argument stop:
#               Stops manage_my_process
#               Deletes the file /var/run/my_process.pid
#               Displays manage_my_process stopped
#       When passing the argument restart
#               Stops manage_my_process
#               Deletes the file /var/run/my_process.pid
#               Starts manage_my_process
#               Creates a file containing its PID in /var/run/my_process.pid
#               Displays manage_my_process restarted
#       Displays Usage: manage_my_process {start|stop|restart} if any other argument or no argument is passed


