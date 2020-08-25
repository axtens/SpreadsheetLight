# SpreadsheetLight
My fork of Vincent Tan's life-saving tool

I have not changed anything of note other than targeting a more recent DocumentFormat.OpenXML and making the code more C#6-ish.

Added references to System.Drawing and System.Windows.Forms. 

Commented out the references to SmartTags. 

With Refactoring Essentials, Roslynator and Roslynator Refactorings tools installed, had an interesting time learning about the kind of C# one ends up with after those tools have a look at one's code. For example:

			dictBuiltInNumberingFormat = new Dictionary<int, string>
			{
				[0] = SLConstants.NumberFormatGeneral,
				[1] = "0",
				[2] = "0.00",
				[3] = "#,##0",
				[4] = "#,##0.00",
				[9] = "0%",
				[10] = "0.00%",
				[11] = "0.00E+00",
				[12] = "# ?/?",
				[13] = "# ??/??", ...
