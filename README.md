Local PlayerSection = Player:NewSection("Esp")

ESPbtn.Name = "ESPbtn"
ESPbtn.Parent = Booga
ESPbtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
ESPbtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
ESPbtn.BorderSizePixel = 2
ESPbtn.Position = UDim2.new(0.364978909, 0, 0.487179488, 0)
ESPbtn.Size = UDim2.new(0, 116, 0, 27)
ESPbtn.Font = Enum.Font.SourceSansSemibold
ESPbtn.Text = "ESP"
ESPbtn.TextColor3 = Color3.new(1, 1, 1)
ESPbtn.TextScaled = true
ESPbtn.TextSize = 14
ESPbtn.TextWrapped = true

ESPbtn.MouseButton1Click:Connect(function()
    for i,v in pairs(Important.Players:GetChildren()) do
        
        CreateESP(v)      
    end
end)
