
<div id="formdiv" style="width:100%;">
<input id="name" type="text" placeholder="Name" class="form" style="font-size:4vmin;" required><br>
<input id="email" type="email" placeholder="Email"class="form" style="font-size:4vmin;" required><br>
<textarea id="msgform" class="form" placeholder="How can we help you?" style="font-size:4vmin;resize:none;" rows="6">
</textarea>
<br>
<button class="form" style="width:auto;border-radius:10%;font-size:4vmin;margin-bottom:20px;color:white;" onclick="send()">
Send
</button>
</div>

<script type="text/javascript" src="https://cdn.emailjs.com/dist/email.min.js"></script>
<script src="email.js"></script>
<!-- Start of Async Drift Code -->
<script>
"use strict";

!function() {
  var t = window.driftt = window.drift = window.driftt || [];
  if (!t.init) {
    if (t.invoked) return void (window.console && console.error && console.error("Drift snippet included twice."));
    t.invoked = !0, t.methods = [ "identify", "config", "track", "reset", "debug", "show", "ping", "page", "hide", "off", "on" ],
    t.factory = function(e) {
      return function() {
        var n = Array.prototype.slice.call(arguments);
        return n.unshift(e), t.push(n), t;
      };
    }, t.methods.forEach(function(e) {
      t[e] = t.factory(e);
    }), t.load = function(t) {
      var e = 3e5, n = Math.ceil(new Date() / e) * e, o = document.createElement("script");
      o.type = "text/javascript", o.async = !0, o.crossorigin = "anonymous", o.src = "https://js.driftt.com/include/" + n + "/" + t + ".js";
      var i = document.getElementsByTagName("script")[0];
      i.parentNode.insertBefore(o, i);
    };
  }
}();
drift.SNIPPET_VERSION = '0.3.1';
drift.load('r6mhyp5d97hf');
</script>
