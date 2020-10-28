---
layout: slide
title: "Welcome to our second slide!"
---
It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)

#Headers#
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
    
#Emphasis#
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

#Lists#

##Unordered##
* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
##Ordered##
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   
##Images##
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

##Blockquotes##
As Kanye West said:

> We're living the future so
> the present is our past.
##Inline code##
I think you should use an
`<addr>` element here instead.

#GitHub Flavored Markdown#

Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:

##Syntax highlighting##
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

You can also simply indent your code by four spaces:
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    
Here’s an example of Python code without syntax highlighting:
def foo():
    if not bar:
        return True
        
##Task Lists##       
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

##Tables##
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

##Issue references within a repository##
Any number that refers to an Issue or Pull Request will be automatically converted into a link.
#1
mojombo#1
mojombo/github-flavored-markdown#1

##Username @mentions##
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

##Automatic linking for URLs##
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.

##Strikethrough##
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.
see: ~~Any word wrapped with two tildes (like ~~this~~) will appear crossed out.~~

##Emoji##
GitHub supports emoji!

To see a list of every image we support, check out the Emoji Cheat Sheet: https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md
    :slightly_smiling_face: :grinning:  :smiley:    :laughing:  :rofl:  :wink:  :blush:	:innocent:  :thinking:
    :zipper_mouth_face: :neutral_face:  :unamused:	:grimacing: :smirk: :roll_eyes: :lying_face:
    :mask:  :sunglasses:    :confused:  :astonished:    :cry:   	:disappointed:
    :raised_hand:   :crossed_fingers:   :ok_hand:   	:point_left:	:point_right:   :point_up_2:    :point_down:    :thumbsup:/:+1: :thumbsdown:/:-1:
    :pray:  :clap:  :handshake: :eyes:  :tongue:    :bearded_person:    :lotus_position:    	:lotus_position_man:    :family_man_woman_girl: 
    :unicorn:   :snail: :sunflower: :construction:  :stop_sign: :ambulance: :hourglass: :alarm_clock:   :clock1230: 	:clock3:    	:bug:   :beetle:
    :sun_with_face: :star:  :stars:	:star2: 	:zap:   	:fire:  	:snowflake: :trophy:    :1st_place_medal:   	:2nd_place_medal:   :3rd_place_medal:
    :football:  :basketball:    :baseball:  	:dart:  	:spades::hearts::diamonds::clubs::black_joker:  
    :mute:  :speaker:   :sound: :loud_sound:    	:bell:  :iphone:    :battery::computer::cd:	:dvd:   	:mag:	:mag_right: :bulb:
    :bookmark_tabs:	:bookmark: 	:label: :dollar: :chart:    :e-mail::envelope::mailbox::pencil2::pen:   :date::calendar:	:wastebasket::lock: :key::closed_lock_with_key:
    :gear::link::hammer_and_wrench::shield: :warning::no_entry::radioactive::biohazard:
    	:arrow_upper_right:	:arrow_lower_left:	:left_right_arrow::leftwards_arrow_with_hook:   :repeat::pause_button::stop_button::eject_button::rewind::fast_forward::arrow_forward:	:arrow_backward:
        	:heavy_multiplication_x::heavy_plus_sign::heavy_minus_sign:	:heavy_division_sign::infinity:
            :bangbang::interrobang::question:	:grey_question:	:grey_exclamation::exclamation::heavy_dollar_sign::hash::zero::seven::keycap_ten:
            :large_orange_diamond::small_orange_diamond:	:large_blue_diamond::small_blue_diamond::black_circle::black_large_square:	:black_medium_square:	:black_medium_small_square:	:black_small_square::checkered_flag::us:	:bowtie:


Use the left arrow to go back!
