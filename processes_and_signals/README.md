# Shell, processes and signals

- 0-what-is-my-pid: displays its own PID
- 1-list_your_processes: lists all processes, user-oriented, with hierarchy
- 2-show_your_bash_pid: shows the process lines containing bash (without pgrep)
- 3-show_your_bash_pid_made_easy: shows PID and name of bash processes (without ps)
- 4-to_infinity_and_beyond: prints "To infinity and beyond" forever, sleeping 2 seconds
- 5-dont_stop_me_now: stops 4-to_infinity_and_beyond using kill
- 6-stop_me_if_you_can: stops 4-to_infinity_and_beyond without kill or killall
- 7-highlander: loops forever and prints "I am invincible!!!" on SIGTERM
- 67-stop_me_if_you_can: stops 7-highlander without kill or killall
- 8-beheaded_process: kills 7-highlander with SIGKILL
- 10-process_and_pid_file: writes a PID file, handles SIGTERM, SIGINT and SIGQUIT
- manage_my_process: writes "I am alive!" to /tmp/my_process every 2 seconds
- 11-manage_my_process: init script supporting start, stop and restart
