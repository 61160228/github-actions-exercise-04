#Hello world docker

This actions prints "Hello world" or "Hello" + the name of person to great

## Inputs

## 'who-to-greet'
**Required** The name of the person to great. Default '"World"'.

## Outputs

## 'time'

The time we greeted you

## Example usage
uses: actions/hello-world-docker-actions@v1
with:
    who-to-greet: 'Mona the Octocat'