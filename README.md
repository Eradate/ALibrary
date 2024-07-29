# ALibrary


```
local UILibrary = loadstring(game:HttpGet"https://raw.githubusercontent.com/Eradate/ALibrary/main/MyLibr"))()

local ui = UILibrary.new("My Custom UI")

ui:addLabel("This is a label")
ui:addButton("Click Me", function()
    print("Button Clicked!")
end)
ui:addToggle("Toggle Option", function(state)
    print("Toggle state:", state)
end)
ui:addTextbox("Enter text here...", function(text)
    print("Text entered:", text)
end)
ui:addDropdown({
    Title = "Choose an option",
    Items = {"Option 1", "Option 2", "Option 3"},
    Callback = function(selected)
        print("Selected:", selected)
    end
})
