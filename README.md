# YJIT bench histograms

CPU: AMD Ryzen 7 5800X

Tested ruby versions:

- 3.2.2
- 3.2.2 --yjit
- 3.2.2 --mjit
- 3.3.0-preview2
- 3.3.0-preview2 --yjit
- 3.3.0-preview2 --mjit
- truffleruby 23.1.0 --native
- truffleruby 23.1.0 --jvm

Links:

- [Headline time ms (median)](#headline-time-ms-median)
- [Headline memory consumption (MB)](#headline-memory-consumption-mb)
- [Micro time ms (median)](#micro-time-ms-median)
- [Micro memory consumption (MB)](#micro-memory-consumption-mb)
- [Other time ms (median)](#other-time-ms-median)
- [Other memory consumption (MB)](#other-memory-consumption-mb)

## Headline time ms (median)

![Headline Time ms (median)] (./histograms/headline_time_ms.svg)

## Headline memory consumption (MB)

![Headline Time ms (median)] (./histograms/headline_mem_mb.svg)

## Micro time ms (median)

![Micro Time ms (median)] (./histograms/micro_time_ms.svg)

## Micro memory consumption (MB)

![Micro Time ms (median)] (./histograms/micro_mem_mb.svg)

## Other time ms (median)

![Other Time ms (median)] (./histograms/other_time_ms.svg)

## Other memory consumption (MB)

![Other Time ms (median)] (./histograms/other_mem_mb.svg)
