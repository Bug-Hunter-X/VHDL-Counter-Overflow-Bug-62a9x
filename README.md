This repository demonstrates a common but easily overlooked bug in VHDL: counter overflow.  The provided VHDL code implements a simple counter. However, it lacks proper handling of the upper bound of the counter. This can lead to unexpected behavior, particularly in simulation and synthesis. The solution demonstrates how to correctly handle the upper bound to prevent overflow.