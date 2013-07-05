namespace ReusableComponents.Views.Helpers
{
    using System;
    using System.Collections.Generic;
    using System.IO;
    using System.Linq;
    using System.Net;
    using System.Text;
    using System.Web;
    using System.Web.Helpers;
    using System.Web.Mvc;
    using System.Web.Mvc.Ajax;
    using System.Web.Mvc.Html;
    using System.Web.Routing;
    using System.Web.Security;
    using System.Web.UI;
    using System.Web.WebPages;
    
    [System.CodeDom.Compiler.GeneratedCodeAttribute("RazorGenerator", "1.1.0.0")]
    public static class TwitterHelpers
    {
        public static System.Web.WebPages.HelperResult 
                             TweetButton(string url, string text) {
            return new System.Web.WebPages.HelperResult(__razor_helper_writer => {
                WebViewPage.WriteLiteralTo(@__razor_helper_writer, 
                    "<script src=\"http://platform.twitter.com/widgets.js\" "+
                    "type=\"text/javascript\">" +
                    "</script>\r\n");

                WebViewPage.WriteLiteralTo(@__razor_helper_writer, 
                    "<div>\r\n" +
                    "<a href=\"http://twitter.com/share\" "+
                    "class=\"twitter-share-button data-url=\""
                );

                WebViewPage.WriteTo(@__razor_helper_writer, url);

                WebViewPage.WriteLiteralTo(@__razor_helper_writer, "\" data-text=\"\'");

                WebViewPage.WriteTo(@__razor_helper_writer, text);

                WebViewPage.WriteLiteralTo(@__razor_helper_writer, 
                    "\'\">Tweet</a>\r\n" +
                    "</div>\r\n"
                );
            });
        }
    }
}
