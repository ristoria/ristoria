LABEL : start
IF PIXEL FOUND : 1907997 : 0 : 1 : 350 : 881 : 355 : 1086
GOTO : workout
ELSE
IF PIXEL FOUND : 0 : 0 : 1 : 169 : 157 : 172 : 329
GOTO : eat 1
ELSE
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 100
GOTO : start
LABEL : eat 1
Keyboard : D6 : KeyPress
DELAY : 10
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 3000
Keyboard : D6 : KeyPress
DELAY : 10
IF PIXEL FOUND : 0 : 0 : 1 : 169 : 157 : 172 : 329
GOTO : eat 4
ELSE
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 100
GOTO : start
LABEL : eat 4
Keyboard : T : KeyPress
DELAY : 10
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 3000
Keyboard : T : KeyPress
DELAY : 10
IF PIXEL FOUND : 0 : 0 : 1 : 169 : 157 : 172 : 329
GOTO : eat 5
ELSE
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 100
GOTO : start
LABEL : eat 5
Keyboard : Y : KeyPress
DELAY : 10
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 3000
Keyboard : Y : KeyPress
DELAY : 10
IF PIXEL FOUND : 0 : 0 : 1 : 169 : 157 : 172 : 329
GOTO : eat 2
ELSE
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 100
GOTO : start
LABEL : eat 2
DELAY : 10
Keyboard : D7 : KeyPress
DELAY : 10
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 3000
Keyboard : D7 : KeyPress
DELAY : 10
IF PIXEL FOUND : 0 : 0 : 1 : 169 : 157 : 172 : 329
GOTO : eat 3
ELSE
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 100
GOTO : start
LABEL : eat 3
DELAY : 10
Keyboard : R : KeyPress
DELAY : 10
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 3000
Keyboard : R : KeyPress
DELAY : 10
GOTO : eat 1
ELSE
Mouse : 0 : 0 : Click : 0 : 1 : 0
DELAY : 100
GOTO : start
