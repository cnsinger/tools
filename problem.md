* screen中色彩设置不生效
 * 原因便是screen没有设置256color生效
 * 需要添加以下语句:
    > termcapinfo xterm 'Co#256:AB=\E[48;5;%dm:AF=\E38;5;%dm'
    > defbce "on"
