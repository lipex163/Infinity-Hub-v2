local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Infinity Hub" .. Fluent.Version,
    TabWidth = 120,
    Size = UDim2.fromOffset(460, 360),
    Acrylic = true,
    Theme = "Dark",
    MinimizeKey = Enum.KeyCode.LeftControl
})

local Tabs = {
    fruits = Window:AddTab({ Title = "Blox Fruits" }),
    king = Window:AddTab({ Title = "King Legacy" }),
    fish = Window:AddTab({ Title = "Fisch" }),
    arsenal = Window:AddTab({ Title = "Arsenal" }),
    rivals = Window:AddTab({ Title = "Rivals" }),
    universal = Window:AddTab({ Title = "Universal" }),
    Settings = Window:AddTab({ Title = "Settings" })
}

Tabs.fruits:AddButton({ Title = "RedZ", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))()
    Fluent:Notify({ Title = "Enjoy!!", Content = "Succefully execute script" })	
end })

Tabs.fruits:AddButton({ Title = "Mukuro Hub", Callback = function() 
    loadstring(game:HttpGet("https://auth.quartyz.com/scripts/Loader.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "W-Azure", Callback = function() 
    loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "Zenith Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Efe0626/RaitoHub/main/Script"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "Speed Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed20Hub20X.lua", true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "MaMa Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/MAMAhub1/Mmahub/main/README.md"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "Fruit Founder", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/flerci42/Adminus_FruitSniper_V2/main/.lua", true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })
Tabs.fruits:AddButton({ Title = "Alchemy Hub", Callback = function() 
    loadstring(game:HttpGet("https://scripts.alchemyhub.xyz"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "Zen Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Zenhubtop/zen_hub_pr/main/zennewwwwui.lua", true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "HoHo Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "Relz Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/farghii/relzhub/main/execute.hack", true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "Beliware", Callback = function() 
    loadstring(game:HttpGet('https://raw.githubusercontent.com/beliveri12/beliware/master/Loader.lua'))('Beliware On Top?') 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "God Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/kiciahook/kiciahook/refs/heads/main/loader.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "Solix Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/debunked69/Solixreworkkeysystem/refs/heads/main/solix20new20keyui.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fruits:AddButton({ Title = "Kncrypt", Callback = function() 
    loadstring(game.HttpGet(game,'https://raw.githubusercontent.com/Yumiara/Python/refs/heads/main/BloxFruit-XYZ.lua'))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.arsenal:AddButton({ Title = "Ronix Hub", Callback = function() 
    loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/93f86be991de0ff7d79e6328e4ceea40.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.arsenal:AddButton({ Title = "BerTox", Callback = function() 
    loadstring(game:HttpGet("https://pastebin.com/raw/8ysy7ENG",true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.arsenal:AddButton({ Title = "Unnamed Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JackyPoopoo/cartel/main/0000000000000000000000000000000000000000000000000"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.king:AddButton({ Title = "TC Hub", Callback = function() 
    loadstring(game:HttpGet("https://github.com/KV-TCode/DonateMe/releases/download/TC_Hub/Loader.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.king:AddButton({ Title = "Tsuo Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Tsuo7/TsuoHub/main/king20legacy"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Speed Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed20Hub20X.lua", true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "CupPink", Callback = function() 
    loadstring(game:HttpGet("https://you.whimper.xyz/sources/CupPink/fisch.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Ronix Hub", Callback = function() 
    loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/f3ac013da72a3b41d6c63454b2749624.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Zenith Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Efe0626/RaitoHub/main/Script"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Project Spectrum 8.0", Callback = function() 
    loadstring(game:HttpGet("https://you.whimper.xyz/spectrum"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Rinns Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/kylosilly/femboyware/refs/heads/main/Fisch.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Pulse", Callback = function() 
    loadstring(game:HttpGet("https://github.com/Synergy-Networks/products/raw/main/Pulse/loader.lua", true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Kncrypt Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/Kncrypt/refs/heads/main/sources/Fisch.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Space Hub", Callback = function() 
    loadstring(game:HttpGet("https://you.whimper.xyz/sources/rb/fisch.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Sewitz", Callback = function() 
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/sewitz-pro/sewitz-pro/main/zXen/ScriptBeta/Sewitz-Fisch.lua")))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Zen Ware", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/LarsScripts/Fisch/refs/heads/main/ZenWare",true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Space Hub Crack", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/venoxcc/universalscripts/refs/heads/main/fisch",true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Reaper Hub", Callback = function() 
    loadstring(game:HttpGet("https://reaperscripts.com/loader.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Goomba Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JustLevel/goombahub/main/fisch.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Spectrum Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/xZPUHigh/Project-Spectrum/main/Loader.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Unknow", Callback = function() 
    (loadstring or load)(game:HttpGet("https://raw.githubusercontent.com/Native-lab/Native/main/loader.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.fish:AddButton({ Title = "Smorg X Chaos", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/MIKEDRIPZOWSKU/test/refs/heads/main/SmorgXChaosFisch.txt", true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.rivals:AddButton({ Title = "Nicuse Hub", Callback = function() 
    loadstring(game:HttpGet("https://nicuse.xyz/Rivals.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.rivals:AddButton({ Title = "Ventures", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Severity-svc/Ventures/refs/heads/main/MainScript.lua"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.rivals:AddButton({ Title = "Desire Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/welomenchaina/Desire-s/refs/heads/main/desire20hub20rules"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.rivals:AddButton({ Title = "Swirl Hub", Callback = function() 
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/FlamesGamesO/FlamezHub/refs/heads/main/main.lua'),true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.universal:AddButton({ Title = "Infinite Yield", Callback = function() 
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.universal:AddButton({ Title = "Remote Spy", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/lipex163/RemoteSpy/refs/heads/main/README.md"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.universal:AddButton({ Title = "UNC Check", Callback = function() 
    loadstring(game:HttpGet("https://pastebin.com/raw/QLn8auCa"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.universal:AddButton({ Title = "Unammed ESP", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/lipex163/Unammed-ESP1.0/refs/heads/main/README.md", true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.universal:AddButton({ Title = "Dex V4", Callback = function() 
    loadstring(game:HttpGet("https://gist.githubusercontent.com/dannythehacker/1781582ab545302f2b34afc4ec53e811/raw/ee5324771f017073fc30e640323ac2a9b3bfc550/dark%20dex%20v4"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.king:AddButton({ Title = "Zen Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Zenhubtop/zen_hub_pr/main/zennewwwwui.lua", true))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

Tabs.king:AddButton({ Title = "Arc Hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JuninhoOGado/ScriptsSite/main/Script286"))() 
    Fluent:Notify({ Title = "Enjoy!!", Content = "Successfully execute script" }) 
end })

SaveManager:SetLibrary(Fluent)
InterfaceManager:SetLibrary(Fluent)

SaveManager:IgnoreThemeSettings()

SaveManager:SetIgnoreIndexes({})

InterfaceManager:SetFolder("FluentScriptHub")
SaveManager:SetFolder("FluentScriptHub/specific-game")

InterfaceManager:BuildInterfaceSection(Tabs.Settings)
SaveManager:BuildConfigSection(Tabs.Settings)


Window:SelectTab(1)

SaveManager:LoadAutoloadConfig()
