# Powershell
My Powershell modules / scripts

  Powershell
  ├───Scripts
  │   └───ScriptName
  │         ├───Source
  │         └───Tests
  │             └───    [...]
  └───Modules
      └───ModuleName
            ├───Source
            │   ├───en-UK
            │   │       about_ModuleBuilder.help.txt
            │   ├───Private
            │   │       CopyHelp.ps1
            │   │       CopyReadme.ps1
            │   │       InitializeBuild.ps1
            │   │       ParameterValues.ps1
            │   │       ParseLineNumber.ps1
            │   │       ResolveModuleManifest.ps1
            │   │       ResolveModuleSource.ps1
            │   │       ResolveOutputFolder.ps1
            │   │       SetModuleContent.ps1
            │   └───Public
            │           Build-Module.ps1
            │           Convert-CodeCoverage.ps1
            │           Convert-LineNumber.ps1
            └───Tests
                ├───Private
                │       [...]
                └───Public
                        [...]
