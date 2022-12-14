PyMinify

A python library for simplifying System Functions.
Created by [vyzv](https://github.com/vyzv)

# Functions

```diff
+ Clear Cmd
+ Adjust Title
+ Align Center
+ Size of Cmd
+ Sleep Command
```
Contributions and feature requests are very welcome! [Issues Page](https://github.com/vyzv/satispy/issues) here.

## Terminal Size
<p><i><strong>Adjust Terminal Size in your Code.</strong></i></p>

```python
from pyminify import Size

Pyminify.Size(120, 32) # (120, 32) is normal terminal size
```

## Center Alignment
<p><i><strong>Align text from print statement in center.</strong></i></p>

```python
from pyminify import Center

print(Pyminify.Center("hello world"))
```
Credits to pycenter

## Cmd Title
<p><i><strong>Adjust a Cmd Title in your favor.</strong></i></p>

```python
from pyminify import Title

Pyminify.Title("hello world")
```

## Clear Command
<p><i><strong>Clear Terminal or Cmd Quickly.</strong></i></p>

```python
from pyminify import Clear

Pyminify.Clear()
```

## Sleep Command
<p><i><strong>Make the Programm sleep.</strong></i></p>

```python
from pyminify import Sleep

Pyminify.Sleep(3) # makes the programm sleep for 3 seconds
```
> <3
