# Hello world!

``` c#
public class Me
{
    public string Name => "Malthe Bjerregaard Petersen";
    public CultureInfo Language => new CultureInfo("da");
    public RegionInfo Country => new RegionInfo("DK");
    
    public string[] GetSoMeAccounts() 
    {
        return new string[] 
        {
            "https://twitter.com/malthe_bp",
            "https://www.linkedin.com/in/malthe-petersen/"
        };
    }
    
    public string GetCurrentWorkPlace()
    {
        return "Novicell DK - Aarhus";
    }
    
    public CultureInfo[] GetSecondaryLanguages()
    {
        return new CultureInfo[]
        {
            new CultureInfo("en")
        };
    }
}
```
