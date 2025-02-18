# KAPE-EZToolsAncillaryUpdater
A PowerShell script that updates [KAPE](https://www.kroll.com/en/insights/publications/cyber/kroll-artifact-parser-extractor-kape) (using `Get-KAPEUpdate.ps1`) as well as [EZ Tools](https://ericzimmerman.github.io/#!index.md) (within `.\KAPE\Modules\bin`) and the ancillary files that enhance the output of those tools.

## What Does "Ancillary" mean?

Per Oxford, `ancillary` means:
  
> providing necessary support to the primary activities or operation of an organization, institution, industry, or system.
    
Used in a sentence:
    
> the development of ancillary services to support its products

In the context of this script, KAPE [Targets](https://github.com/EricZimmerman/KapeFiles/tree/master/Targets)/[Modules](https://github.com/EricZimmerman/KapeFiles/tree/master/Modules), [EvtxECmd Maps](https://github.com/EricZimmerman/evtx/tree/master/evtx/Maps), [SQLECmd Maps](https://github.com/EricZimmerman/SQLECmd/tree/master/SQLMap/Maps), and [RECmd Batch files](https://github.com/EricZimmerman/RECmd/tree/master/BatchExamples) are ancillary to their respective tools. Each of these files enhance the output of their respective tools. Keeping them updated is often overlooked but very important to ensuring that you're benefitting from the latest features/bug fixes from [Eric Zimmerman](https://github.com/EricZimmerman) and the latest work from the DFIR community. 

## Where Do I Run the Script From?

![ScriptLocation](https://github.com/rathbuna/KAPE-EZToolsAncillaryUpdater/blob/main/Pictures/ScriptLocation.jpg)

Right-click -> `Run with PowerShell` and let it ride!

## Usage Examples

Want to use KAPE with .NET 4 EZ Tools binaries? Run this command: `.\KAPE-EZToolsAncillaryUpdater.ps1 4`

Want to use KAPE with .NET 6 EZ Tools binaries? Run this command: `.\KAPE-EZToolsAncillaryUpdater.ps1 6`

Make sure you have the [.NET 6 Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) installed prior to using the .NET 6 version of EZ Tools with KAPE!

# Improving the Script
Do you see something that could be done better with this script? Create an issue or do a Pull Request, if so! This is the first script I've put together on my own so I have no doubts there's room for improvement. Anything that moves the ball forward and helps the DFIR community I will always be in full support of!
