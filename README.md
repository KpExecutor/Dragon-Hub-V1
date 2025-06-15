--carregar biblioteca 
 local= loadstring(game:HttpGet("https://githulocal Window = Fluent:CreateWindow({
 
   Title = "Dragon Hub V1 " .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})


local Tabs = {
    Main = Window:AddTab({ Title = "scripts" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
--Parágrafos
Tabs.Main:AddParagraph({ Title = "Bem vindo, ao Dragon Hub !/", Content = "Discord Na Bio do meu canal !" })
--Botões
Tabs.Main:AddButton({ Title = "Auto Farm", Callback = function() 
 loadstring(game:HttpGet("https://github.com/loladamlol/Blox-Fruits-Script.git
end })
Tabs.Main:AddButton({ Title = "Auto Bounty Script", Callback = function() 
loadstring(game:HttpGet("https://github.com/kukucoolboy79/-Blox-Fruits-Script-Hub-2025-Best-Keyless-Auto-Farm-Aimbot-Bounty.git
end })
Tabs.Main:AddButton({ Title = "Auto Mirage", Callback = function() 
loadstring(game:HttpGet("https://github.com/lattex6329/bloxfruits.git
 end})
 
Window:SelectTab(1)
Fluent:Notify({ Title = "Fluent", Content = "The script has been loaded." })

