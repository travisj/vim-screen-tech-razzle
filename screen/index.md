!SLIDE

# connecting to screen
## screen -D -RR

!SLIDE

# moving around
* ctrl-a 0-9
* ctrl-a n
* ctrl-a p
* ctrl-a ctrl-a
* ctrl-a ' / name or number
* ctrl-a " / select using j/k & enter

!SLIDE

# other commands
* new window: ctrl-a c
* name window: ctrl-a shift-a
* scroll: ctrl-a esc / movement (j, k, ctrl-b, ctrl-f)
* kill window: ctl-a shift-k
* see all commands: ctrl-a ?

!SLIDE

# screenrc
	@@@
	vbell on
	nethack on 
	vbell_msg ""
	autodetach on
	startup_message off
	pow_detach_msg "Screen session of \$LOGNAME \$:cr:\$:nl:ended."
	shell -$SHELL
	msgminwait 3

	hardstatus alwayslastline "%{.cb}%-W%{.rW}%50L> %n %t%{-}%+W%L<%-37=%{+b}%{.bc} %D %Y-%m-%d %{.bY}%c%{-b} %{.bc}%l "

## [my .srceenrc](https://gist.github.com/08601a46afc1a4297e31)
