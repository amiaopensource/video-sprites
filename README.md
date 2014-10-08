# Video::Sprites

TODO: Write a gem description

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'video-sprites'
```

## Usage

### Options

Interval: Optional. Time between the snapshots. (Default 5 seconds.)

Width:  Optional. Width of the each thumbnail. (Default 200.)

Columns: Number of columns in the sprite. (Default 5.)

KeepGenerated: Keep all the individual images and other intermediate artifacts.

Input: Input file or directory. (Default: Current working directory.)
Output: Output directory. (Default: Current working directory with "output" directory.)


```shell
video-sprites --interval 5 --width 200 --columns 5 --keepgenerated --input . --output ./output
```

