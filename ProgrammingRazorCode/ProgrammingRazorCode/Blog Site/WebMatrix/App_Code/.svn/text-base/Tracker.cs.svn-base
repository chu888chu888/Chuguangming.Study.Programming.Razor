using System;
using System.Collections.Generic;
using System.Web;

public static class Tracker
{
    private static readonly IList<string> Hits = new List<string>();

    public static string Track(string name)
    {
        Hits.Add(name);
        return string.Empty;
    }

    public static IHtmlString Report()
    {
        return new HtmlString("<div>" + string.Join("</div><div>", Hits) + "</div>");
    }

    public static void Clear()
    {
        Hits.Clear();
    }
}
