```C#
OmidPakdelGithubProfile.IntroduceMySelf();

class OmidPakdelGithubProfile
{
    private static string Name { get; set; } = "Omid Pakdel";
    private static int Age { get; set; } = 23;
    private static string Role { get; set; } = "Software Engineer";
    private static List<string> Stack { get; set; } = new() {".NET", "django rest framework", "Angular"};
    private static string Email { get; set; } = "pakdel.dev@gmail.com";

    public static void IntroduceMySelf()
    {
        Console.WriteLine("Hello fellow devs!");
        Console.WriteLine($"I'm {Name}, {Age}.");
        Console.WriteLine($"I'm a {Role} using {string.Join(", ", Stack)}.");
        Console.WriteLine($"If you wanna contact me, here is my email: {Email}");
        Console.WriteLine("Hope you enjoy ur time while u r here :)");
    }
}
```
