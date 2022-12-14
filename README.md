<h1 align="center">SatisPy</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
  <img alt="License: MIT" src="https://img.shields.io/github/license/vyzv/satispy" />
</p>

> Satispy is a python library for simplifying System Functions.
> <br>
> Created by [vyzv](https://github.com/vyzv)

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
from satispy import Size

Satispy.Size(120, 32) # (120, 32) is normal terminal size
```

## Center Alignment
<p><i><strong>Align text from print statement in center.</strong></i></p>

```python
from satispy import Center

print(Satispy.Center("hello world"))
```
Credits to pycenter

## Cmd Title
<p><i><strong>Adjust a Cmd Title in your favor.</strong></i></p>

```python
from satispy import Title

Satispy.Title("hello world")
```

## Clear Command
<p><i><strong>Clear Terminal or Cmd Quickly.</strong></i></p>

```python
from satispy import Clear

Satispy.Clear()
```

## Sleep Command
<p><i><strong>Make the Programm sleep.</strong></i></p>

```python
from satispy import Sleep

Satispy.Sleep(3) # makes the programm sleep for 3 seconds
```
> <3
