### Welcome
You may know the problem: You quickly want to create a new class and it's just stupid work to write all the getter and setter methods. This plugin should solve that problem for you.

![Screenshot](https://github.com/nbussman/coda2-getter_setter/raw/master/screenshot.png)

### Installation
Just download the plugin, open it with Coda 2 and you'll be fine. 

### How it works
The script will search for stuff like this:
```
private $name;
public  $address;
protected $phone ="232323";
```
and will past the getter and/or setter right where your cursor is.
Like this:
```
public function get_phone(){
    return $phone;
}
```

###Regulare Expression
This is the regulare expression i used. I'm absolutely new to this, so if you got better  ideas just send them to me.
```
~public \s*\$([A-Za-z0-9-_]+)\s*.*;\s*~i
```
###Shortcuts
Actually there aren't any shortcuts. If you wish to have some, just post me.

### Support or Contact
Having trouble with the plugin? Just send me a message. I try to help you.