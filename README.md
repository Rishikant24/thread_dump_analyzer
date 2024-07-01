<!--- -*-markdown-*- -->

# Java Thread Dump Analyzer

This is a Java thread dump analyzer written in Javascript built on top of https://github.com/spotify/threaddump-analyzer

<!-- # License

The Java Thread Dump Analyzer is licensed under
[version 2.0 of the Apache license](http://www.apache.org/licenses/LICENSE-2.0.html),
the copyright belongs to Spotify AB. -->

# Testing Locally

Pull/Download the repository
```bash
npm install
```

Right click on index.html and open with the browser of your choice

Tested with `npm` `6.13.7` and `node` `v13.8.0`.

## Using the Analyzer

1. Choose if you want to analyze a jstack/jmap

2. Then if there are any specific Thread States that you are interested in or certain keywords that your team is interested in and want to look out for, add those in the form fields

3. You can either copy-paste the text in the text-box and then click on analyze or select a file by clicking on the Choose File option.

4. Voila! Your results are displayed below.

## Quick Notes

Since this repo is built on top of another repo which used only html and pure js, the components do not dynamically render, and thus it is advisable to refresh the page before multiple runs :)
