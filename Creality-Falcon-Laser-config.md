# Creality Falcon Laser Module

```
Grbl 1.3a ['$' for help]

$
[HLP:$$ $# $G $I $N $x=val $Nx=line $J=line $SLP $C $X $H $F ~ ! ? ctrl-x]
```

## Implemented configuration values

|Code           | Description     |
|---------------|-----------------|
$0=10           | [Step pulse, microseconds](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#0--step-pulse-microseconds)
$1=250          | [Step idle delay, milliseconds](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#1---step-idle-delay-milliseconds)
$2=0            | [Step port invert, mask](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#2--step-port-invert-mask)
$3=3            | [Direction port invert, mask](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#3--direction-port-invert-mask)
$4=0            | [Step enable invert, boolean](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#4---step-enable-invert-boolean)
$5=0            | [Limit pins invert, boolean](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#5----limit-pins-invert-boolean)
$6=0            | [Probe pin invert, boolean](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#6----probe-pin-invert-boolean)
$10=1           | [Status report, mask](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#10---status-report-mask)
$11=0.010       | [Junction deviation, mm](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#11---junction-deviation-mm)
$12=0.002       | [Arc tolerance, mm](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#12--arc-tolerance-mm)
$13=0           | [Report inches, boolean](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#13---report-inches-boolean)
$20=0           | [Soft limits, boolean](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#20---soft-limits-boolean)
$21=0           | [Hard limits, boolean](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#21---hard-limits-boolean)
$22=1           | [Homing cycle, boolean](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#22---homing-cycle-boolean)
$23=3           | [Homing dir invert, mask](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#23---homing-dir-invert-mask)
$24=1500.000    | [Homing feed, mm/min](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#24---homing-feed-mmmin)
$25=4500.000    | [Homing seek, mm/min](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#25---homing-seek-mmmin)
$26=20          | [Homing debounce, milliseconds](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#26---homing-debounce-milliseconds)
$27=3.000       | [Homing pull-off, mm](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#27---homing-pull-off-mm)
$30=1000.000    | [Max spindle speed, RPM](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#30---max-spindle-speed-rpm)
$31=0.000       | [Min spindle speed, RPM](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#31---min-spindle-speed-rpm)
$32=1           | [Laser mode, boolean](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#32---laser-mode-boolean)
$100=80.000     | [X steps/mm](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#100-101-and-102--xyz-stepsmm)
$101=80.000     | [Y steps/mm](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#100-101-and-102--xyz-stepsmm)
$110=10000.000  | [X Max rate, mm/min](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#110-111-and-112--xyz-max-rate-mmmin)
$111=10000.000  | [Y Max rate, mm/min](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#110-111-and-112--xyz-max-rate-mmmin)
$120=500.000    | [X Acceleration, mm/sec^2](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#120-121-122--xyz-acceleration-mmsec2)
$121=500.000    | [Y Acceleration, mm/sec^2](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#120-121-122--xyz-acceleration-mmsec2)
$130=220.000    | [X Max travel, mm](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#130-131-132--xyz-max-travel-mm)
$131=220.000    | [Y Max travel, mm](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#130-131-132--xyz-max-travel-mm)

## No implemented configuration values

|Code           | Description     |
|---------------|-----------------|
$102            | [Z steps/mm](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#100-101-and-102--xyz-stepsmm)
$112            | [Z Max rate, mm/min](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#110-111-and-112--xyz-max-rate-mmmin)
$122            | [Z Acceleration, mm/sec^2](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#120-121-122--xyz-acceleration-mmsec2)
$131            | [Z Max travel, mm](https://github.com/gnea/grbl/blob/master/doc/markdown/settings.md#130-131-132--xyz-max-travel-mm)
