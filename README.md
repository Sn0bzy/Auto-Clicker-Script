# Auto Clicker Script
You can click buttons on websites with this code

## Usage

1. You must edit code for target button. (See the configuration below)
2. Go to taget website and press F12 (open Console) 
3. Paste the code and set click times (change '[CLICK TIMES]' to '1000' or want do you want)
4. Press enter and wait

## Configuration 

`jQuery('.[BUTTON CLASS]').each(function(index, value) { setTimeout(function() { jQuery(value).trigger('click'); }, index * [CLICK TIMES]); });`

You should configure code like this

`jQuery('.btn-small').each(function(index, value) { setTimeout(function() { jQuery(value).trigger('click'); }, index * 5000); });`

## Credits

Hasan CAN - https://hasan.im
