# dcss_hit_chance

WIP: The theory of probability based chance to hit calculator.

Usage: 
* Download [hit_chance.txt](hit_chance.txt) and add it to your `crawl/settings` directory.

* Add those lines to init.txt:
```
{
function ready()
  HitChance()
end
}
```

You will get notice if you reequip yourself about your chance to hit. 


Feel free to contribute some pull requests. I need some good data for `local monsters` variable, that calculates actual `EV` of monsters this dungeon level.
