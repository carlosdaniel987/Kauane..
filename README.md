-- carregar biblioteca
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

-- carregamento 

Fluent:Notify({
    Title = "Bem-vindo",
    Content = "Interface carregada com sucesso!"
})

-- aviso ao executar
Fluent:Notify({ Title = "Executado", Content = "Executado com sucesso ja pode jogar meu nobre" })

local Window = Fluent:CreateWindow({
    Title = "KAUANE♥️" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "BLUE"
})

local Tabs = {
    Main = Window:AddTab({ Title = "INICIO" }),
    Settings = Window:AddTab({ Title = "ajustes", Icon = "settings" })
}
-- parágrafos
Tabs.Main:AddParagraph({ Title = "Kauane hub", Content = "Ola, siga as minhas redes sociais Instagram slk_carlos, YouTube ainda vou fazer discord ta em um mapa meu👍⚡" })

-- botões
Tabs.Main:AddButton({ Title = "Rael hub op", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt")() end})
Tabs.Main:AddButton({ Title = "speed wave", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/speedwavevip/scriptspeed/refs/heads/main/Brookhaven_lraq"))() end })
Tabs.Main:AddButton({ Title = "BROOKHAVEN", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/BROOKHAVEN-GUI-/main/METAB", true))() end })
Tabs.Main:AddButton({ Title = "EQ CARL", Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/eQA4nfcw"))() end })
Tabs.Main:AddButton({ Title = "CENTRAL BR", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptCentral-br/SCU/refs/heads/main/sc.md",true))() end })
Tabs.Main:AddButton({ Title = "SANDER X CARL", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/NormalSS.lua'))() end })
Tabs.Main:AddButton({ Title = "G HUB CARL", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBV14XZ/main/Ghub_Main_Loader.txt"))() end })
Tabs.Main:AddButton({ Title = "CARL HUB OLD", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/carlosdaniel987/Carl-hub-novo/refs/heads/main/README.md")() end })
