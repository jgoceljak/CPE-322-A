## GTKwave and GHDL
## Hello World

```
$ ghdl -h
$ ghdl -v
$ ghdl -a hello.vhdl
$ ghdl -e hello_world
$ ghdl -r hello_world
Hello world!
```

![Helloworld](https://github.com/jgoceljak/CPE-322-A/blob/d6cc7fbfc8f52b8c8e19c22ca0ba20cf0ff9a5b4/Lab%201/hello%20world%20commands.png)
## Half Adder

```
$ ghdl -a ha.vhdl
$ ghdl -a ha_tb.vhdl
$ ghdl -e ha_tb
$ ghdl -r ha_tb --vcd=ha.vcd
ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test
$ gtkwave ha.vcd
```
![Half adder cmd](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/half%20adder%20commands.png)
![half adder](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/half%20adder.png)


## Full Adder

```
$ ghdl -a adder.vhdl
$ ghdl -a adder_tb.vhdl
$ ghdl -e adder_tb
$ ghdl -r adder_tb --vcd=adder.vcd
adder_tb.vhdl:54:5:@8ns(assertion note): end of test
$ gtkwave adder.vcd
```
![adder cmd](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/adder%20comands.png)
![adder](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/full%20adder.png)

## D Flip Flop

```
$ ghdl -a dff.vhdl
$ ghdl -a dff_tb.vhdl
$ ghdl -e dff_tb
$ ghdl -r dff_tb --vcd=dff.vcd
$ gtkwave dff.vcd
```
![D flip flop cmd](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/flipflop%20commands.png)
![D flip flop](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/flipflip%20.png)

## T Flip Flop

```
$ ghdl -a tff.vhdl
$ ghdl -a tff_tb.vhdl
$ ghdl -e tff_tb
$ ghdl -r tff_tb --vcd=tff.vcd
$ gtkwave tff.vcd
```
![T flip flop cmd](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/t-flipflop%20commands.png)
![T flip flop](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/t-flipflop.png)

## 4-1 Multiplexer

```
$ ghdl -a mux.vhdl
$ ghdl -a mux_tb.vhdl
$ ghdl -e mux_tb
$ ghdl -r mux_tb --vcd=mux.vcd
$ gtkwave mux.vcd
```
![4-1 multiplexer cmd](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/multiplexer%20commands.png)
![4-1 multiplexer](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/multiplexer.png)

## Demultiplexer

```
$ ghdl -a demux.vhdl
$ ghdl -a demux_tb.vhdl
$ ghdl -e demux_tb
$ ghdl -r demux_tb --vcd=demux.vcd
$ gtkwave demux.vcd
```
![Demultiplexer cmd](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/deplexer%20commands.png)
![demultiplexer](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/deplexer.png)

## 8-bit square root

```
$ ghdl -a --ieee=synopsys sqrt8.vhdl
$ ghdl -e --ieee=synopsys sqrt8
$ ghdl -r --ieee=synopsys sqrt8 --stop-time=512ns > sqrt8.out
$ cat sqrt8.out
$ ghdl -r --ieee=synopsys sqrt8 --stop-time=512ns --vcd=sqrt8.vcd
```
![square root cmd](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/square%20root%20commands%201.png)
![square root cmd 2](https://github.com/jgoceljak/CPE-322-A/blob/013e36e08401e017d76eed7844f8639565611cb8/Lab%201/square%20root%20commands%202.png)


