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
## Half Adder

```
$ ghdl -a ha.vhdl
$ ghdl -a ha_tb.vhdl
$ ghdl -e ha_tb
$ ghdl -r ha_tb --vcd=ha.vcd
ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test
$ gtkwave ha.vcd
```
## Full Adder

```
$ ghdl -a adder.vhdl
$ ghdl -a adder_tb.vhdl
$ ghdl -e adder_tb
$ ghdl -r adder_tb --vcd=adder.vcd
adder_tb.vhdl:54:5:@8ns(assertion note): end of test
$ gtkwave adder.vcd
```
## D Flip Flop

```
$ ghdl -a dff.vhdl
$ ghdl -a dff_tb.vhdl
$ ghdl -e dff_tb
$ ghdl -r dff_tb --vcd=dff.vcd
$ gtkwave dff.vcd
```

## T Flip Flop

```
$ ghdl -a tff.vhdl
$ ghdl -a tff_tb.vhdl
$ ghdl -e tff_tb
$ ghdl -r tff_tb --vcd=tff.vcd
$ gtkwave tff.vcd
```

## 4-1 Multiplexer

```
$ ghdl -a mux.vhdl
$ ghdl -a mux_tb.vhdl
$ ghdl -e mux_tb
$ ghdl -r mux_tb --vcd=mux.vcd
$ gtkwave mux.vcd
```

## Demultiplexer

```
$ ghdl -a demux.vhdl
$ ghdl -a demux_tb.vhdl
$ ghdl -e demux_tb
$ ghdl -r demux_tb --vcd=demux.vcd
$ gtkwave demux.vcd
```

## 8-bit square root

```
$ ghdl -a --ieee=synopsys sqrt8.vhdl
$ ghdl -e --ieee=synopsys sqrt8
$ ghdl -r --ieee=synopsys sqrt8 --stop-time=512ns > sqrt8.out
$ cat sqrt8.out
$ ghdl -r --ieee=synopsys sqrt8 --stop-time=512ns --vcd=sqrt8.vcd
```

