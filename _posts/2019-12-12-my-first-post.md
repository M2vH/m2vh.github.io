---
layout: post
title: "My first post!"
category: test
tags: test helloWorld m2vh
---

Date: {{ page.date }}

# {{ page.title }}

This is the _**first**_ post to check the functionaluty of Jekyll blog mechanism.

I hope I will understand it ;-)

## Hello World!

The title of this post is set using `page.title` as shown here

```markdown
## {{ "{{ page.title " }}}}
```

Writing about code id pretty easy.  
Some text using `code` or a complete codeblock like the following:

```csharp
// lexer: csharp
using System;
namespace M2vH{
    class Me{
        string name = "Marco M. von Hagen";
    }
}
```

### Example of lexers.html.XmlLexer and XAML

```xml
<!-- lexer: xml -->
<Page
    x:Class="Prototype_UWP_CS.MainPage"
    xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
    xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
    xmlns:local="using:Prototype_UWP_CS"
    xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
    xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
    mc:Ignorable="d"
    Background="{ThemeResource ApplicationPageBackgroundThemeBrush}">

    <Grid>

    </Grid>
</Page>

```

---
