### Improvements to Grid star-rows space allocating algorithm

|   |   |
|---|---|
|Details|Fixed a bug in the [algorithm for allocating sizes to *-rows](https://github.com/Microsoft/dotnet/blob/master/Documentation/compatibility/wpf-grid-allocation-of-space-to-star-columns.md) in a <xref:System.Windows.Controls.Grid> introduced in .NET Framework 4.7.  In some cases, such as a Grid with <code>Height=&quot;Auto&quot;</code> containing empty rows, rows were arranged at the wrong position, possibly outside the Grid altogether.|
|Suggestion|In order for the application to benefit from these changes, it must run on the .NET Framework 4.8 or later.|
|Scope|Major|
|Version|4.8|
|Type|Runtime|
