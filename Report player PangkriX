-- Rayfield Loader
local Rayfield = loadstring(game:HttpGet("https://sirius.menu/rayfield"))()

-- Window
local Window = Rayfield:CreateWindow({
    Name = "Report Player | PangkriX",
    LoadingTitle = "Report Player",
    LoadingSubtitle = "by PangkriX",
    ConfigurationSaving = {
        Enabled = false
    }
})

-- Helper function
local function CopyText(text)
    if setclipboard then
        setclipboard(text)
        Rayfield:Notify({
            Title = "Copied",
            Content = "Report reason copied to clipboard",
            Duration = 2
        })
    end
end

------------------------------------------------
-- TAB 1 : BULLY
------------------------------------------------
local Bully = Window:CreateTab("Bully", 4483362458)

Bully:CreateButton({
    Name = "Avatar",
    Callback = function()
        CopyText("This player is using an avatar item that contains text or imagery meant to mock, insult, or harass other players.")
    end
})

Bully:CreateButton({
    Name = "Game or Experience",
    Callback = function()
        CopyText("This player repeatedly harassed and verbally bullied other players in the experience, creating a hostile and unsafe environment.")
    end
})

Bully:CreateButton({
    Name = "Movement or Emote",
    Callback = function()
        CopyText("This player used emotes and movements to mock, taunt, or harass other players repeatedly during gameplay.")
    end
})

------------------------------------------------
-- TAB 2 : CHEAT
------------------------------------------------
local Cheat = Window:CreateTab("Cheat", 4483362458)

Cheat:CreateButton({
    Name = "Avatar",
    Callback = function()
        CopyText("This player is using or promoting an item that falsely claims to grant special powers, admin abilities, or unfair advantages.")
    end
})

Cheat:CreateButton({
    Name = "Game or Experience",
    Callback = function()
        CopyText("This player is using exploits, hacks, or unfair methods to gain an advantage and disrupt normal gameplay.")
    end
})

Cheat:CreateButton({
    Name = "Movement or Emote",
    Callback = function()
        CopyText("This player used abnormal movement or animation behavior to gain an unfair advantage, suggesting the use of exploits.")
    end
})

------------------------------------------------
-- TAB 3 : SEX
------------------------------------------------
local Sex = Window:CreateTab("Sex", 4483362458)

Sex:CreateButton({
    Name = "Avatar",
    Callback = function()
        CopyText("This player’s avatar item includes sexually suggestive content or themes that are inappropriate for Roblox’s audience.")
    end
})

Sex:CreateButton({
    Name = "Game or Experience",
    Callback = function()
        CopyText("This player engaged in inappropriate sexual or dating behavior in chat and actions that are not suitable for Roblox’s audience.")
    end
})

Sex:CreateButton({
    Name = "Movement or Emote",
    Callback = function()
        CopyText("This player performed sexually suggestive emotes or movements that are inappropriate for Roblox’s audience.")
    end
})

------------------------------------------------
-- TAB 4 : HATE
------------------------------------------------
local Hate = Window:CreateTab("Hate", 4483362458)

Hate:CreateButton({
    Name = "Avatar",
    Callback = function()
        CopyText("This player is wearing or displaying an item that contains hateful symbols, offensive language, or discriminatory messages.")
    end
})

Hate:CreateButton({
    Name = "Game or Experience",
    Callback = function()
        CopyText("This player used hateful language or behavior targeting individuals or groups, which violates Roblox community rules.")
    end
})

Hate:CreateButton({
    Name = "Movement or Emote",
    Callback = function()
        CopyText("This player used emotes or movements to express hateful or offensive gestures toward other players.")
    end
})

------------------------------------------------
-- TAB 5 : OFF PLATFORM LINK
------------------------------------------------
local OffLink = Window:CreateTab("Off Link", 4483362458)

OffLink:CreateButton({
    Name = "Game or Experience",
    Callback = function()
        CopyText("This player shared external links and tried to redirect users to websites or platforms outside of Roblox.")
    end
})

------------------------------------------------
-- TAB 6 : PERSONAL INFO
------------------------------------------------
local Personal = Window:CreateTab("Personal Info", 4483362458)

Personal:CreateButton({
    Name = "Game or Experience",
    Callback = function()
        CopyText("This player asked for or shared personal or private information, putting others’ safety at risk.")
    end
})

------------------------------------------------
-- TAB 7 : SCAMMING
------------------------------------------------
local Scam = Window:CreateTab("Scamming", 4483362458)

Scam:CreateButton({
    Name = "Game or Experience",
    Callback = function()
        CopyText("This player attempted to scam others by promising free Robux, items, or rewards in exchange for trust or actions.")
    end
})

------------------------------------------------
-- TAB 8 : SWEARING
------------------------------------------------
local Swear = Window:CreateTab("Swear", 4483362458)

Swear:CreateButton({
    Name = "Game or Experience",
    Callback = function()
        CopyText("This player used excessive profanity or inappropriate language in chat that is not acceptable on Roblox.")
    end
})

------------------------------------------------
-- TAB 9 : VIOLENCE
------------------------------------------------
local Violence = Window:CreateTab("Violence", 4483362458)

Violence:CreateButton({
    Name = "Game or Experience",
    Callback = function()
        CopyText("This player threatened or promoted real-world violence through chat or in-game behavior.")
    end
})
