# HexaPaper

A super simple python script that creates a **proper** hexagonal paper (see example.pdf), which is, IMHO, super useful for organic chemistry class, but you are free to use it elsewhere ;). Moreover, the script provides an option to draw help lines, which are rather helpful than distracting.

## Requirements

The script uses [reportlab](https://www.reportlab.com/) python package, so the requirements are:

* `Python >=3.9` (Haven't try on previous versions, might work as well)
* `reportlab`

## How to use

Run the following code to get your PDF produced:

```py
python hexa_paperer.py
```

Which with default configuration should produce a `hexa_paper.pdf`

## Configuration

Script is easily configurable with constants in the top of the script, where you can set line color, thickness, page scale, number of help lines, etc.

## License

Distributed under the MIT License. See `LICENSE` for more information.
