---
layout: page
title: Kontakt
permalink: /kontakt/
---

<section class="contact">
    <div class="row">
        <div class="contact-wrap">
            <div class="info-wrap">
                <h2>Nils Torbjörn Petersen, M.A.</h2>
                <p>
                    Multimedia Production
                </p>
                <p>
                    Esmarchstr. 22<br />
                    24105 Kiel
                </p>
                <p>
                    <a href="javascript:linkTo_UnCryptMailto('nbjmup;lpoubluAfoufqf/ef');"><i class="fa fa-envelope"></i> kontakt [at] entepe [dot] de</a>
                </p>
            </div>
            <div class="form-wrap">
                <form action="//formspree.io/kontakt@entepe.de" method="POST" class="pure-form ajax-form">
                    <formbody>
                        <fieldset class="pure-group">
                            <input type="text" class="pure-input-1" placeholder="Name" name="name" required>
                            <input type="email" class="pure-input-1" placeholder="E-Mail" name="_replyto" required>
                        </fieldset>
                        <fieldset class="pure-group">
                            <input type="text" class="pure-input-1" placeholder="Betreff" name="_subject">
                            <textarea class="pure-input-1" placeholder="Nachricht" name="message" rows="6" required></textarea>
                        </fieldset>
                        <input type="text" class="pure-input-1" name="_gotcha" style="display:none">
                        <button type="submit" class="pure-button"><i class="fa fa-paper-plane-o"></i> Abschicken</button>
                    </formbody>
                </form>
            </div>
        </div>
    </div>
</section>

<script type="text/javascript"> <!--
    function UnCryptMailto( s )
    {
        var n = 0;
        var r = "";
        for( var i = 0; i < s.length; i++)
        {
            n = s.charCodeAt( i );
            if( n >= 8364 )
            {
                n = 128;
            }
            r += String.fromCharCode( n - 1 );
        }
        return r;
    }

    function linkTo_UnCryptMailto( s )
    {
        location.href=UnCryptMailto( s );
    }
// --> </script>
