# sv-security-scans-05, 2023-02-15

For the Info Session presentation Fri Feb 17

1. New Public repo
2. Settings


## Presentation Slides

See the file `2023-02-17-github-security-02.pptx`


## Pay attention to Branches

```
  bandit-03-alg
  bandit-03-aws
  bandit-04-alg
  bandit-04-aws
* main
  snyk-01
  snyk-02
```

They contain Bandit scans, direct (-03) and using actions (-04) on two Python 
subdirectories:

```
aws-dynamodb-encryption-python
python-algorithms
```
(Shows how easy it is to implement your own custom scans.)

`snyk-*` branches contain Snyk static analysis scans (free tier).


## https://github.com/.../sv-security-scans-01

Internal repo (no GHAS).

Contains sample workflows with several useful open-source free scanning tools!

