操作步骤
执行以下命令以安装 Obfuscar 全局工具：

# 在项目根目录操作 View->Terminal
dotnet new tool-manifest
# The template "Dotnet local tool manifest file" was created successfully.

dotnet tool install obfuscar.globaltool
# You can invoke the tool from this directory using the following commands: 'dotnet tool run obfuscar.console' or 'dotnet obfuscar.console'.
#Tool 'obfuscar.globaltool' (version '2.2.49') was successfully installed. Entry is added to the manifest file D:\GitHub\obfuscar-example\.config\dotnet-tools.json.

dotnet tool restore
# Restore was successful.

dotnet tool list
dotnet tool run obfuscar --help
dotnet tool run obfuscar.console --help
