# speak-to-me

> A little utility to make your browser talk using the [HTML5 Speech Synth API](http://updates.html5rocks.com/2014/01/Web-apps-that-talk---Introduction-to-the-Speech-Synthesis-API)

App can be found here: http://robatron.github.io/speak-to-me

## Usage

From http://robatron.github.io/speak-to-me, just type what you want to say in the input box and press the `enter` key on your keyboard or the 'Speak!' button.

### Directly in the URL

You can type what you want to say directly into the URL after the `#` symbol, e.g.,

  [http://robatron.github.io/speak-to-me#type what you want to say directly into the URL](http://robatron.github.io/speak-to-me#type what you want to say directly into the url after the hash)

### Obfuscated linking

Grab an base64-ofuscated link to the current saying by copying the link from the link symbol in the top right of the app, e.g., 

  http://robatron.github.io/speak-to-me#B64%3AVGhpcyUyMGlzJTIwYW4lMjBvYmZ1c2NhdGVkJTIwc2F5aW5n

This is useful for linking to coworkers without obviously revealing what the browser is about to say to them!

## Examples

- [The 90s](http://robatron.github.io/speak-to-me#B64%3ATm93JTJDJTIwdGhpcyUyMGlzJTIwYSUyMHN0b3J5JTIwYWxsJTIwYWJvdXQlMjBob3clMjBNeSUyMGxpZmUlMjBnb3QlMjBmbGlwcGVkLXR1cm5lZCUyMHVwc2lkZSUyMGRvd24lMjBBbmQlMjBJJ2QlMjBsaWtlJTIwdG8lMjB0YWtlJTIwYSUyMG1pbnV0ZSUyMEp1c3QlMjBzaXQlMjByaWdodCUyMHRoZXJlJTIwSSdsbCUyMHRlbGwlMjB5b3UlMjBob3clMjBJJTIwYmVjYW1lJTIwdGhlJTIwcHJpbmNlJTIwb2YlMjBhJTIwdG93biUyMGNhbGxlZCUyMEJlbCUyMEFpcg==)
- [Dude looks like a lady](http://robatron.github.io/speak-to-me#B64%3ARGVzY3JpYmUlMjB3aGF0JTIwTWFyc2VsbHVzJTIwV2FsbGFjZSUyMGxvb2tzJTIwbGlrZSE=)
- [A blended ice cream drink](http://robatron.github.io/speak-to-me#B64%3ASGVyZSUyQyUyMGlmJTIweW91JTIwaGF2ZSUyMGElMjBtaWxrc2hha2UlMkMlMjBhbmQlMjBJJTIwaGF2ZSUyMGElMjBtaWxrc2hha2UlMkMlMjBhbmQlMjBJJTIwaGF2ZSUyMGElMjBzdHJhdy4lMjBUaGVyZSUyMGl0JTIwaXMlMkMlMjB0aGF0J3MlMjBhJTIwc3RyYXclMkMlMjB5b3UlMjBzZWUlM0YlMjBXYXRjaCUyMGl0LiUyME5vdyUyQyUyMG15JTIwc3RyYXclMjByZWFjaGVzJTIwYWNyb29vb29vb3NzJTIwdGhlJTIwcm9vbSUyMGFuZCUyMHN0YXJ0cyUyMHRvJTIwZHJpbmslMjB5b3VyJTIwbWlsa3NoYWtlLiUyMEklMjBkcmluayUyMHlvdXIlMjBtaWxrc2hha2Uh)

## Credits

- Icons by [GLYPHICONS ](http://glyphicons.com/)

## Notes

- Use a modified [minimist](https://github.com/substack/minimist) to capture command-line-like arguments from the hash?

## License

The MIT License (MIT)

Copyright (c) 2014 Rob McGuire-Dale

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
