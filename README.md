## Created by Karma Developments, edited by Cisoko. (https://discord.gg/cisoko)

## Exports
Alphabet:
```lua
    exports['skillchecks']:startAlphabetGame(15000, 5, function(result) --time in ms, amount of letters 
        if result then
            print('Success')
        else
            print('Failed')
        end
    end)
```

Lockpick:
```lua
    exports['skillchecks']:startLockpickingGame(15000, 12, 5, function(result) -- time in ms, number of locks, number of levels 
        if result then
            print('Success')
        else
            print('Failed')
        end
    end)
```

Words memory:
```lua
    exports['skillchecks']:startWordsGame(15000, 5, function(result) --time in ms, number of words
        if result then
            print('Success')
        else
            print('Failed')
        end
    end)
```

Untangle:
```lua
    exports['skillchecks']:startUntangleGame(15000, 5, function(result) -- time in ms, number of dots
        if result then
            print('Success')
        else
            print('Failed')
        end
    end)
```

Flood:
```lua
    exports['skillchecks']:startFloodGame(15000, 5, 5, function(result) -- time in ms, move count, size of grid
        if result then
            print('Success')
        else
            print('Failed')
        end
    end, "Name", "Placeholder!", 15000, 5, 5)

Same:
```lua
    exports['skillchecks']:startSameGame(15000, 5, 5, function(result) --time in ms, grid size x, grid size 
        if result then
            print('Success')
        else
            print('Failed')
        end
    end)
```

Flip:
```lua
    exports['skillchecks']:startFlipGame(15000, 5, function(result) -- time in ms, grid size
        if result then
            print('Success')
        else
            print('Failed')
        end
    end)
```

Direction:
```lua
    exports['skillchecks']:startDirectionGame(15000, 2, 3, 7, function(result) -- time in ms, required correct choices, minimal grid size, maximal grid size
        if result then
            print('Success')
        else
            print('Failed')
        end
    end)
```