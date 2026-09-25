# tipeline
tiny ass regexp pipelines for JavaScript

## Usage
`p(string, pipeline)`

`string` is a string that gets passed through the pipeline

`pipeline` is an array with objects with atleast 2 entries

### `pipeline`
the objects in pipeline are like this:

`x` is the regex

`r` is the replacer

`l` is optional, but if set to true, it will repeat until it doesn't change no more
