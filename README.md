# ⚠ Solemn Declaration

This repo was imported from [here]( https://bitbucket.org/boredzo/prhonoffbutton/overview ) at first ( it was hosted on Bitbucket, but I love GitHub rather than the former ).
Its original writer is [Peter Hosey]( https://bitbucket.org/boredzo ), thank you for this awesome framework! And I will continue to develop it.

### Purpose
This is a button cell class that aims to replicate the sliding-switch button, as seen in many iPhone apps and in the Time Machine pane in System Preferences.

### Compatibility
This class works on the Mac (using AppKit). It will not work on the iPhone, where there is no reason for it (it already has a sliding-switch class).
The implementation requires Mac OS X 10.5 or later, primarily for NSGradient.

### Getting started
Add PRHOnOffButton.[hm] and PRHOnOffButtonCell.[hm] to your source code directory, your Xcode project, and the relevant targets.
In IB, add a checkbox to your xib.
Select it. Switch to the Identity (`⌘⌥3` in Xcode 5.x and later) Inspector. Set the control's class to PRHOnOffButton.
Double-click the control to edit its cell. Set the cell's class to PRHOnOffButtonCell.

### Features
* The cell supports the mixed state. You can turn that on in the Attributes (`⌘⌥4` in Xcode 5.x and later) Inspector for your button control. (You probably shouldn't set it for the cell specifically unless it's hosted in a matrix or something instead of a button control.)
* Since it's a cell, it should work in matrixes and table views, although I haven't tested it in a table view.
