# runit
> Ensure consistent use of numbers with units across projects.


## Install

`pip install runit`

## How to use

Turn a dimensionless number into one with units.

```python
with_unit(10, "ton")
```




10 ton



Convert from one unit to another.

```python
tons = ton(3)
to(tons, sunit="pound")
```




6000.0 pound


