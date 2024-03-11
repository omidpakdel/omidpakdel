```C#
OmidPakdelProfile.IntroduceMySelf();

class OmidPakdelProfile
{
    private static string Name { get; } = "Omid Pakdel";
    private static string Role { get; } = "Software Engineer / Backend Developer";
    private static List<string> Skills { get; } = new() { ".NET", "Django REST Framework", "Angular" };
    private static string Email { get; } = "pakdel.dev@gmail.com";
    private static string Location { get; } = "Iran";
    private static string LinkedIn { get; } = "https://linkedin.com/in/omidpakdel";

    public static void IntroduceMySelf()
    {
        Console.WriteLine("👋 Hello, fellow developers!");
        Console.WriteLine($"👤 I'm {Name}, a {Role}.");
        Console.WriteLine($"🛠️ I specialize in: {string.Join(", ", Skills)}.");
        Console.WriteLine($"📫 Reach out to me at: {Email}");
        Console.WriteLine($"🌍 Based in: {Location}");
        Console.WriteLine($"🔗 LinkedIn: {LinkedIn}");
        Console.WriteLine("Hope you enjoy your time while you're here! 😊");
    }
}
```
