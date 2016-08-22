[![Build Status](https://drone.io/github.com/s-urbaniak/agoc/status.png)](https://drone.io/github.com/s-urbaniak/agoc/latest)

## Go Autocompletion for the acme editor

### Usage
Execute 'agoc' in the tag window of an existing .go file. A new window called "+agoc" will open. Whenever you type something in the original source window, a completion will be proposed in the "+agoc" window.

### Installation

	go get github.com/s-urbaniak/agoc

### Prerequisites
You need to have gocode installed:

	go get github.com/nsf/gocode

Also requires latest [plan9port](https://github.com/9fans/plan9port) acme with [focus log event](https://github.com/9fans/plan9port/commit/fdf6ef333705c844bcf3ccf2f93b2773f1a6aa41) support.
