# exp - a command line client for [explainshell.com](http://www.explainshell.com/)

exp is an command line client for [explainshell.com](http://www.explainshell.com/)
it's written in [perl](http://www.perl.org/) and needs only [curl](http://curl.haxx.se/) installed in your system to work

## install

    sudo curl https://raw2.github.com/troydm/exp/master/exp -o /usr/local/bin/exp
    sudo chmod +x /usr/local/bin/exp

## usage

    # print help message
    exp --help

    # print ls -lh command description
    exp ls -lh

    # print echo | grep commands description
    exp 'echo | grep'

## license 

[MIT](http://opensource.org/licenses/MIT)
