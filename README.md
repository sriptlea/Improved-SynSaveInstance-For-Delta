How to use,

local Params = {
	RepoURL = "https://raw.githubusercontent.com/sriptlea/Improved-SynSaveInstance-For-Delta/refs/heads/main/",
	SSI = "ussi",
}

local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()

local CustomOptions = { SaveBytecode = true }

synsaveinstance(CustomOptions)
