# Tflintadate
Init and validate arbitary depth of terraform code in a directory


### Table of Contents

<!-- toc -->

- [Usage](#usage)
  * [Basic](#basic)
- [Inputs](#inputs)
  * [repo](#repo)


<!-- tocstop -->

## Usage

### Basic

Add the following step to your workflow:

```yaml
    - name: Assume OIDC Role
      uses: RentTheRunway/tflintadate@v1
      with:
        repo: <current-repo> 
```
## Inputs

### environment

*required*  
The `repo` input should be a valid repo in the RentTheRunway Org.
