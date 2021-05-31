# Revolutionary-clock-conky-
see https://www.pling.com/p/1006556/ for details 

There is no clock like this as one user said
 "It's pure and utter MADNESS, like some mystifying marvelous work of a mad scientist."

This should work on any full conky installations irrespective of linux distro or flavour.  I tested it on LinuxMint and Arch.

To appreciate this clock you need to see it move. It is distinguished from other such clocks by the clock rings not having a fixed starting position but rather move as a function of time and likewise expand circumferentialy as a function of time. 

Revolutionary clocks comes in 4 sizes: HD, midi, mini & supermini

It is fully configurable. The lua script is explained in the c_n_s_explanation.txt file.

To install just move or copy the " .Conky " hidden folder to your user/home folder! (note capital C for .Conky)

Remember to install the fonts!

To run, changes the propertries of the script file " start_conky.sh " to "is executable" . Then excute it in a terminal. 

To enable conky to start with the system go to " startup applications " and add in the file " .Conky/revolutionary_clock/...x.../start_conky.sh " where ...x... signifies the desired conky size e.g. rev_hd.

It is currently setup to use conky version 1.10 and above. 
For versions 1.9 and below I have left the files called "conkyrc9"  tobe used instead

test in terminal 
conky -c $HOME/.Conky/revolutionary_clocks/rev_hd/conkyrc &


Enjoy!!!
