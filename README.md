prontopasta
===========

server-less, self-contained paste tool

* share text, code, snippets
* save as bookmarklet for taking quick notes
* completely contained within a data-uri
* works off-line

#### See the [example file](https://rawgithub.com/residualmind/prontopasta/master/example.html) for a link containing the actual tool.

Or copy:

    data:text/html;base64,PHRleHRhcmVhIGNvbHM9OTAgcm93cz0yND5EaXRhbGluaSwgQ2FwcGVsbGluaQpUd2lybCBteSBmb3JrIGluIHRoZSBGZXR0dWNpbmkKSGVyZSBjb21lcyBtYW1hIHdpdGggdGhlIGxhc2FnbmEKRXZlcnlib2R5IE1hbmdpYSwgTWFuZ2lhITwvdGV4dGFyZWE+PGJyPjxidXR0b24gb25jbGljaz0iZT1kb2N1bWVudDtkPWUubG9jYXRpb247dz13aW5kb3c7Zj1kLmhyZWY7dT13LmF0b2IoZi5zdWJzdHIoMjIpKTtkLmhyZWY9Zi5zdWJzdHIoMCwyMikrdy5idG9hKHUuc3Vic3RyKDAsMjYpK2UuYm9keS5jaGlsZHJlblswXS52YWx1ZSt1LnN1YnN0cigtMTk4KSkiPmxpbms8L2J1dHRvbj4NCg==

into your browser's URL-bar.


The un-base64d code:

    <textarea cols=90 rows=24></textarea><br>
    <button onclick="e=document;d=e.location;w=window;f=d.href;u=w.atob(f.substr(22)); \
    d.href=f.substr(0,22)+w.btoa(u.substr(0,26)+e.body.children[0].value+u.substr(-198))">link</button>
