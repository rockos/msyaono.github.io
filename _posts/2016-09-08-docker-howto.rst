=============================================================
Docker HOWTO
=============================================================

:Author: AONO Masayuki
:$B=iHG(B: 2015$BG/(B4$B7n(B25$BF|(B
:v2: 2016$BG/(B7$B7n(B7$BF|(B Docker Toolbox$BBP1~$K2~D{(B

$B$O$8$a$K(B
=============================================================

$B%3%s%F%J7?2>A[2=$H%5!<%P2>A[2=$N0c$$$O!"BP>]$,%^%7%s$G$O$J$/%W%m%;%9$K$J$k!#(B
$B%5!<%P2>A[2=$G$O%[%9%H%^%7%s>e$G%2%9%H%^%7%s$,F0$-!"%2%9%H%^%7%sFb$GMM!9$J%W%m%;%9$,F0$/!#%3%s%F%J7?2>A[2=$G$O!"%[%9%H(B OS $B>e$K%3%s%F%J$H$$$&3VN%$5$l$?6u4V$,:n@.$5$l!"$=$NCf$G%W%m%;%9$,<B9T$5$l$k!#(B

$B%3%s%F%JFb$GF0$$$F$$$k$N$O%^%7%s$G$O$J$/C1$J$k%W%m%;%9$G$"$k$?$a!"EvA3$J$,$i(B cron $B$d(B syslog $BEy$NB>$N%W%m%;%9$OF0$$$F$$$J$$!#!V%3%s%F%J$H$$$&3VN%$5$l$?6u4V$G0l$D$N%W%m%;%9$,F0$/!W$H$$$&35G0$r;}$D$3$H!#(B

1. $B%;%C%H%"%C%W<j=g(B
   =============================================================

1. Docker Tool Box $B$r(B `Docker $B$N%5%$%H(B <https://www.docker.com/products/docker-toolbox>`_ $B$+$i%@%&%s%m!<%I(B

$B%"%W%j%1!<%7%g%s%U%)%k%@$K!"0J2<$N#2$D$N%"%$%3%s$,I=<($5$l$k!#(B

* Kitematic$B!J(BGUI$B%D!<%k!K(B

  Docker$B%3%s%F%J$r0lMw$7$?$j!"@_Dj$rD4@0$7$?$j$G$-$k(BGUI$B%D!<%k!#(B
    Downloadingocker Hub$B$+$i%$%a!<%8$rDI2C$7$?$j$G$-$k!#(B

    * Docker Quickstart Terminal

      $B%/%j%C%/$9$k$H!"(BDocker$BMQ%[%9%H$r5/F0$7!"(BMac$B>e$+$iA`:n$9$k$?$a$N4D6-JQ?t$J$I$r@_Dj$7$?>e$G!"%?!<%_%J%k(B(iTerm)$B$,5/F0$9$k!#(B

      docker $B$N4D6-@_Dj$H$7$F0J2<$r(B bash_profile $B$KDI2C$9$k(B ::

        $ eval $(docker-machine env default)

