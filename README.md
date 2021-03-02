# SnowFlake for Raku

## USAGE

```raku
use SnowFlake;

my $worker = SnowFlake.new(worker_id => 1, sequence => 2);
say $worker.get_id();
```