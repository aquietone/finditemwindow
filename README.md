# Find Item Window

This lua script recreates the find item window from live EQ for EMU servers where it does not exist.  

In addition, it has some very, very simple cross toon search capabilities using MQ2DanNet, which can be used to find and request items from other online toons. It doesn't have the most robust logic for requesting items, and will only attempt one time as long as they are in the same zone and within trading distance of the requesting character.  

![](./images/find.png)  

![](./images/search.png)  

## Installation

Download `find.lua` and place it into your MQ lua folder.

## Usage

Start the script with `/lua run find`.  

Open the find window when the script is already running with `/findwindow`.
