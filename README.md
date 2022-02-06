# Hello world!

``` c#
public class Me
{
    public string Name => "Malthe Bjerregaard Petersen";
    public CultureInfo Culture => new CultureInfo("da-DK");
    
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
    
    public string[] GetSecondaryLanguages()
    {
        return new string[]
        {
            new CultureInfo("en").DisplayName
        }
    }
}
```
