# Simple Windows Printer
Windows Print Server and Printer Monitoring management Pack for SCOM 2016 and later.

This MP is a conversion of the Tasty.Printer.Monitoring MP by Tyson Paul.  Changes include:

1. Simplified Windows Print Server class model (only one generic class)
2. Elimination of Windows 2003 MP, Windows 2008 MP and Windows 2012 MP dependencies
3. Additional Knowledge articles
4. Additional display names

## Object Classes
Windows Print Server Role (Simple.Windows.Printer.PrintServer.Role)
Windows Printer (Simple.Windows.Printer.PrintServer.Printer)

## Discoveries
Simple.Windows.Printer.PrintServer.Role.Discovery
Simple.Windows.Printer.PrintServer.Printer.Discovery

## Monitors
Simple.Windows.Printer.SpoolerService.Monitor
Simple.Windows.Printer.PrintServer.Printer.Monitor
