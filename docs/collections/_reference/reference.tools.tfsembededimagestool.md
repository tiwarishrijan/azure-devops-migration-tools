---
optionsClassName: TfsEmbededImagesToolOptions
optionsClassFullName: MigrationTools.Tools.TfsEmbededImagesToolOptions
configurationSamples:
- name: defaults
  description: 
  code: >-
    {
      "MigrationTools": {
        "CommonTools": {
          "TfsEmbededImagesTool": {
            "Enabled": "True"
          }
        }
      }
    }
  sampleFor: MigrationTools.Tools.TfsEmbededImagesToolOptions
- name: sample
  description: 
  code: >-
    {
      "MigrationTools": {
        "CommonTools": {
          "TfsEmbededImagesTool": {
            "Enabled": "True"
          }
        }
      }
    }
  sampleFor: MigrationTools.Tools.TfsEmbededImagesToolOptions
- name: classic
  description: 
  code: >-
    {
      "$type": "TfsEmbededImagesToolOptions",
      "Enabled": true
    }
  sampleFor: MigrationTools.Tools.TfsEmbededImagesToolOptions
description: missng XML code comments
className: TfsEmbededImagesTool
typeName: Tools
architecture: 
options:
- parameterName: Enabled
  type: Boolean
  description: If set to `true` then the tool will run. Set to `false` and the processor will not run.
  defaultValue: missng XML code comments
status: missng XML code comments
processingTarget: missng XML code comments
classFile: /src/MigrationTools.Clients.AzureDevops.ObjectModel/Tools/TfsEmbededImagesTool.cs
optionsClassFile: /src/MigrationTools.Clients.AzureDevops.ObjectModel/Tools/TfsEmbededImagesToolOptions.cs

redirectFrom:
- /Reference/Tools/TfsEmbededImagesToolOptions/
layout: reference
toc: true
permalink: /Reference/Tools/TfsEmbededImagesTool/
title: TfsEmbededImagesTool
categories:
- Tools
- 
topics:
- topic: notes
  path: /docs/Reference/Tools/TfsEmbededImagesTool-notes.md
  exists: false
  markdown: ''
- topic: introduction
  path: /docs/Reference/Tools/TfsEmbededImagesTool-introduction.md
  exists: false
  markdown: ''

---