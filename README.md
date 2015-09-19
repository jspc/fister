Fister
==

Fisting: its like fingering,but beter innit

Rationale
--

`finger` is a good tool fraught with issues; both security issues and privacy. It runs in plain text, it has access to a user's `.plan` and `.project` files requiring root permissions.

`fister`, on the other hand:

 * Runs via the ssh protocol to avoid MITM attcks
 * Uses PGP to sign messages to avoid tampering
 * Stores user plan and project data in  key/value pair to avoid elevated permissions
 * Returns only the content a user discloses

In this respect the tool should be pretty useful for larger networks where walkups are both inevitable and inevitably annoying.

Licence
--

The MIT License (MIT)

Copyright (c) 2015 jspc

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
