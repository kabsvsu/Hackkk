local menu = script.Parent.Parent.Frame

script.Parent.MouseButton1Click:Connect(function()
    menu.Visible = not menu.Visible
end)

menu.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
