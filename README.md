# AWSCloudFormation
AWSCloudFormation samples in JSON and YAML

# AWS CloudFormation Template Flip

## About

AWS CloudFormation Template Flip is a tool that converts [AWS CloudFormation](https://aws.amazon.com/cloudformation/) templates between [JSON](http://json.org/) and [YAML](http://yaml.org) formats, making use of the YAML format’s short function syntax where possible.

The term "Flip" is inspired by the well-known Unix command-line tool [flip](https://ccrma.stanford.edu/~craig/utility/flip/) which converts text files between Unix, Mac, and MS-DOS formats.

## Installation

AWS CloudFormation Template Flip can be installed using [pip](https://pip.pypa.io/en/stable/):

```bash
pip install cfn_flip
```

## Usage

AWS CloudFormation Template Flip is both a command line tool and a python library.

Note that the command line tool is spelled `cfn-flip` with a hyphen, while the python package is `cfn_flip` with an underscore.

### Command line tool

    Usage: cfn-flip [OPTIONS] [INPUT] [OUTPUT]

      AWS CloudFormation Template Flip is a tool that converts AWS
      CloudFormation templates between JSON and YAML formats, making use of the
      YAML format's short function syntax where possible."

    Options:
      -j, --json     Convert to JSON. Assume the input is YAML.
      -y, --yaml     Convert to YAML. Assume the input is JSON.
      -c, --clean    Performs some opinionated cleanup on your template.
      -l, --long     Use long-form syntax for functions when converting to YAML.
      -n, --no-flip  Don't convert. If you use -n in conjunction with -j or -y,
                     the input format is assumed to be the same as the output
                     format you specify.
      --help         Show this message and exit.
