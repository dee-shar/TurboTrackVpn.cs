# TurboTrackVpn.cs
Mobile-API for [TurboTrack VPN](https://play.google.com/store/apps/details?id=com.turbotrackvpn) application an ultimate solution for unlocking the full potential of your online experience!

## Example
```cs
using TurboTrackVpnApi;

namespace Application
{
    internal class Program
    {
        static async Task Main()
        {
            var api = new TurboTrackVpn();
            string servers = await api.GetServers("uuid");
            Console.WriteLine(servers);
        }
    }
}
```
