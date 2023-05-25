<div class="regular contents"><div class="cooked"><p>Namaste Mitro ,</p>
<p>I have bring up a guide to show custom popup on textbox something like<br>
</p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/a/aa0fc2bf118d02078eb91c20c692ba0be538a736.jpeg" data-download-href="https://community.niotron.com/uploads/default/aa0fc2bf118d02078eb91c20c692ba0be538a736" title="popup example"><img src="https://community.niotron.com/uploads/default/optimized/2X/a/aa0fc2bf118d02078eb91c20c692ba0be538a736_2_345x120.jpeg" alt="popup example" data-base62-sha1="ogqW6wiTl6oNCDe1B5S0YeWf0Eu" srcset="https://community.niotron.com/uploads/default/optimized/2X/a/aa0fc2bf118d02078eb91c20c692ba0be538a736_2_345x120.jpeg, https://community.niotron.com/uploads/default/optimized/2X/a/aa0fc2bf118d02078eb91c20c692ba0be538a736_2_517x180.jpeg 1.5x, https://community.niotron.com/uploads/default/optimized/2X/a/aa0fc2bf118d02078eb91c20c692ba0be538a736_2_690x240.jpeg 2x" data-dominant-color="F1F3F5" style="aspect-ratio: 345 / 120;" loading="lazy" width="345" height="120"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">popup example</span><span class="informations">800×279 9.06 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p>So lets get started</p>
<p>Let’s get look on components and extensions we have used</p>
<p><img src="https://community.niotron.com/uploads/default/original/2X/3/3772885c27c7fcdf12b4b0f71b48ddf3a25c64b2.png" alt="components" data-base62-sha1="7UvE3458YlBYkRfxbqjeqQP0Vnc" style="aspect-ratio: 189 / 487;" loading="lazy" width="189" height="487"></p>
<p>Extension used</p>
<ol>
<li>Component Tools</li>
<li>Repositioning Tools</li>
<li><a href="https://community.niotron.com/t/free-videolayout-extension/2166">Keyboard <span class="badge badge-notification clicks" title="5 clicks">5</span></a></li>
<li><a href="https://community.niotron.com/t/free-floating-action-view-customized-version-of-a-fab-extension/4398">List Finder By Atom Developer <span class="badge badge-notification clicks" title="6 clicks">6</span></a></li>
<li><a>String Tools [Sorry but i don’t get extension on any other community so I am uploading direct extension here]</a></li>
</ol>
<p>Now Let’s go through the blocks section</p>
<p>What is my logic that First I have registered components tools component as my textbox<br>
</p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/8/88431b4dc119e85def092231dbd3e43124e38c6e.png" data-download-href="https://community.niotron.com/uploads/default/88431b4dc119e85def092231dbd3e43124e38c6e" title="blocks (1)"><img src="https://community.niotron.com/uploads/default/optimized/2X/8/88431b4dc119e85def092231dbd3e43124e38c6e_2_345x66.png" alt="blocks (1)" data-base62-sha1="jrqI6l4FDBtLkOaBxXVxrEAkKMS" srcset="https://community.niotron.com/uploads/default/optimized/2X/8/88431b4dc119e85def092231dbd3e43124e38c6e_2_345x66.png, https://community.niotron.com/uploads/default/optimized/2X/8/88431b4dc119e85def092231dbd3e43124e38c6e_2_517x99.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/8/88431b4dc119e85def092231dbd3e43124e38c6e_2_690x132.png 2x" data-dominant-color="A18A8E" style="aspect-ratio: 345 / 66;" loading="lazy" width="345" height="66"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">blocks (1)</span><span class="informations">934×180 7.62 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p>Then when components tools touched its an event to get position of component on clicked<br>
First create variables to store positions of touched</p>
<p><img src="https://community.niotron.com/uploads/default/original/2X/f/f380578904aee8543119a7bcf93837d5aa33bf1f.png" alt="blocks (3)" data-base62-sha1="yK6ZN6ycpeaLShlNJDwihO0JIED" style="aspect-ratio: 189 / 26;" loading="lazy" width="189" height="26"><br>
This will store x position on touched<br>
<img src="https://community.niotron.com/uploads/default/original/2X/0/0bd085aae4ae85f766def0f376865d70b804196b.png" alt="blocks (4)" data-base62-sha1="1Gw0xOAiCNKs4uMHfdVmcWDfNsD" style="aspect-ratio: 189 / 26;" loading="lazy" width="189" height="26"><br>
This will store y position on touched<br>
<img src="https://community.niotron.com/uploads/default/original/2X/a/aefce8ba2b81cc47af3089a62403ac0aefef3544.png" alt="blocks (5)" data-base62-sha1="oY0VYtb4SWehcm951cBzi28HM2w" style="aspect-ratio: 340 / 26;" loading="lazy" width="340" height="26"><br>
This will store action like touch up, touch down , moved etc , I have used this block to create double click on component.</p>
<p></p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/e/e930c562f517351d8ef9e46c0576b685fad06418.png" data-download-href="https://community.niotron.com/uploads/default/e930c562f517351d8ef9e46c0576b685fad06418" title="blocks (2)"><img src="https://community.niotron.com/uploads/default/optimized/2X/e/e930c562f517351d8ef9e46c0576b685fad06418_2_345x243.png" alt="blocks (2)" data-base62-sha1="xgTK0AtvGdHRMCQw6lPLLan59zO" srcset="https://community.niotron.com/uploads/default/optimized/2X/e/e930c562f517351d8ef9e46c0576b685fad06418_2_345x243.png, https://community.niotron.com/uploads/default/optimized/2X/e/e930c562f517351d8ef9e46c0576b685fad06418_2_517x364.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/e/e930c562f517351d8ef9e46c0576b685fad06418_2_690x486.png 2x" data-dominant-color="AE8178" style="aspect-ratio: 345 / 243;" loading="lazy" width="345" height="243"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">blocks (2)</span><span class="informations">988×696 34.4 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p>In this block I have added request focus because when I register component[textbox] it remove focus and also used that Keyboard extension to show keyboard , then I have stored actions into a variable as a list because action won’t get event onDouble Clicked on a component So it will store ACTION_UP,ACTION_DOWN and MOVE, So we are checking when user double click means when user double touched up it will raise a popup yes , getting till now ? Any doubt ? If yes, Comment bellow. I have also stored x and y position in a variable so that after the event double click raise we get the current position.</p>
<p><strong>Lets move ahead to check if touch is double clicked or not</strong><br>
</p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/d/d4352ab542ebf7acc0cdc891fc7c0acfe7dbffb3.png" data-download-href="https://community.niotron.com/uploads/default/d4352ab542ebf7acc0cdc891fc7c0acfe7dbffb3" title="blocks (6)"><img src="https://community.niotron.com/uploads/default/optimized/2X/d/d4352ab542ebf7acc0cdc891fc7c0acfe7dbffb3_2_407x375.png" alt="blocks (6)" data-base62-sha1="uhh8fMSJTpNwYaJFyM5wh4lngBB" srcset="https://community.niotron.com/uploads/default/optimized/2X/d/d4352ab542ebf7acc0cdc891fc7c0acfe7dbffb3_2_407x375.png, https://community.niotron.com/uploads/default/optimized/2X/d/d4352ab542ebf7acc0cdc891fc7c0acfe7dbffb3_2_610x562.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/d/d4352ab542ebf7acc0cdc891fc7c0acfe7dbffb3_2_814x750.png 2x" data-dominant-color="B67776" style="aspect-ratio: 407 / 375;" loading="lazy" width="407" height="375"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">blocks (6)</span><span class="informations">1456×1340 78.5 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p>Before this block we have search for text in the variable list yes, after we get the no of items{length of items} if they are 2 it means it’s double clicked else single or tripple so another we are checking wether textbox is empty or not, then we are clearing the list so that this process run on every double click, then we are setting position of our custom popup view with the help of Repositioning Tools then I have set clock enabled timer interval is 7000 , you have seen in many apps that after double click the popup hides yes same as that.</p>
<p>This is basic set up you can edit next blocks after you create your custom popup.<br>
I am posting blocks of current app</p>
<p></p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/7/7a4cbb5868134d658b057d4f8681393223900f88.png" data-download-href="https://community.niotron.com/uploads/default/7a4cbb5868134d658b057d4f8681393223900f88" title="blocks (7)"><img src="https://community.niotron.com/uploads/default/optimized/2X/7/7a4cbb5868134d658b057d4f8681393223900f88_2_345x62.png" alt="blocks (7)" data-base62-sha1="hrUEd34rtSSGzBP3y3c1Q36jshi" srcset="https://community.niotron.com/uploads/default/optimized/2X/7/7a4cbb5868134d658b057d4f8681393223900f88_2_345x62.png, https://community.niotron.com/uploads/default/optimized/2X/7/7a4cbb5868134d658b057d4f8681393223900f88_2_517x93.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/7/7a4cbb5868134d658b057d4f8681393223900f88_2_690x124.png 2x" data-dominant-color="66A296" style="aspect-ratio: 345 / 62;" loading="lazy" width="345" height="62"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">blocks (7)</span><span class="informations">712×130 7.21 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p><img src="https://community.niotron.com/uploads/default/original/2X/8/8eee5efbf49c6bca5426eb0f18f0c72fd94a72d6.png" alt="blocks (8)" data-base62-sha1="koqvwegQyFScai9foiP7K9K0WtE" style="aspect-ratio: 331 / 117;" loading="lazy" width="331" height="117"></p>
<p></p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/6/6aacfd48dc6d8a1ce0422307610556e6852ced44.png" data-download-href="https://community.niotron.com/uploads/default/6aacfd48dc6d8a1ce0422307610556e6852ced44" title="blocks (9)"><img src="https://community.niotron.com/uploads/default/optimized/2X/6/6aacfd48dc6d8a1ce0422307610556e6852ced44_2_345x61.png" alt="blocks (9)" data-base62-sha1="fdHeSiI6BwW2lnwXGStlktxUcRe" srcset="https://community.niotron.com/uploads/default/optimized/2X/6/6aacfd48dc6d8a1ce0422307610556e6852ced44_2_345x61.png, https://community.niotron.com/uploads/default/optimized/2X/6/6aacfd48dc6d8a1ce0422307610556e6852ced44_2_517x91.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/6/6aacfd48dc6d8a1ce0422307610556e6852ced44_2_690x122.png 2x" data-dominant-color="65A495" style="aspect-ratio: 345 / 61;" loading="lazy" width="345" height="61"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">blocks (9)</span><span class="informations">726×130 6.57 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p></p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/8/88311243afecad45b476f3b601f586552f51c851.png" data-download-href="https://community.niotron.com/uploads/default/88311243afecad45b476f3b601f586552f51c851" title="blocks (11)"><img src="https://community.niotron.com/uploads/default/optimized/2X/8/88311243afecad45b476f3b601f586552f51c851_2_345x133.png" alt="blocks (11)" data-base62-sha1="jqO4omnTU742ZDSlW5WqgEcEuOZ" srcset="https://community.niotron.com/uploads/default/optimized/2X/8/88311243afecad45b476f3b601f586552f51c851_2_345x133.png, https://community.niotron.com/uploads/default/optimized/2X/8/88311243afecad45b476f3b601f586552f51c851_2_517x199.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/8/88311243afecad45b476f3b601f586552f51c851_2_690x266.png 2x" data-dominant-color="8B8295" style="aspect-ratio: 345 / 133;" loading="lazy" width="345" height="133"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">blocks (11)</span><span class="informations">1320×510 27.4 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p></p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/7/7b59edb02c55c370ecfd554c2a881e7882e230ac.png" data-download-href="https://community.niotron.com/uploads/default/7b59edb02c55c370ecfd554c2a881e7882e230ac" title="blocks (12)"><img src="https://community.niotron.com/uploads/default/optimized/2X/7/7b59edb02c55c370ecfd554c2a881e7882e230ac_2_345x88.png" alt="blocks (12)" data-base62-sha1="hBdoMx2LMTcddf95E5w2d3H5wIs" srcset="https://community.niotron.com/uploads/default/optimized/2X/7/7b59edb02c55c370ecfd554c2a881e7882e230ac_2_345x88.png, https://community.niotron.com/uploads/default/optimized/2X/7/7b59edb02c55c370ecfd554c2a881e7882e230ac_2_517x132.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/7/7b59edb02c55c370ecfd554c2a881e7882e230ac_2_690x176.png 2x" data-dominant-color="8D9A70" style="aspect-ratio: 345 / 88;" loading="lazy" width="345" height="88"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">blocks (12)</span><span class="informations">1110×286 14.9 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p></p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/a/aa56cc2070a8f70adc207336db6c773b282e8885.png" data-download-href="https://community.niotron.com/uploads/default/aa56cc2070a8f70adc207336db6c773b282e8885" title="blocks (13)"><img src="https://community.niotron.com/uploads/default/optimized/2X/a/aa56cc2070a8f70adc207336db6c773b282e8885_2_345x106.png" alt="blocks (13)" data-base62-sha1="oiT8dgCIbhlsSCSN6YE95MTnPhz" srcset="https://community.niotron.com/uploads/default/optimized/2X/a/aa56cc2070a8f70adc207336db6c773b282e8885_2_345x106.png, https://community.niotron.com/uploads/default/optimized/2X/a/aa56cc2070a8f70adc207336db6c773b282e8885_2_517x159.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/a/aa56cc2070a8f70adc207336db6c773b282e8885_2_690x212.png 2x" data-dominant-color="8A948A" style="aspect-ratio: 345 / 106;" loading="lazy" width="345" height="106"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">blocks (13)</span><span class="informations">1418×436 27.8 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p>I am requesting to use this guide if you are knowing atleast basic of niotron which is how component are used.</p>
<p>Thankyou <img src="https://community.niotron.com/images/emoji/twitter/slightly_smiling_face.png?v=12" title=":slightly_smiling_face:" class="emoji" alt=":slightly_smiling_face:" loading="lazy" style="aspect-ratio: 20 / 20;" width="20" height="20"> Hope you like this guide</p>
<p>Please go to the logic and don’t just copy paste</p>
<p><a href="https://community.niotron.com/uploads/short-url/kMoXKPVpAoUrhX1QeZ74udsRZu9.aia">AIA File</p>
<p><a href="https://community.niotron.com/uploads/short-url/AkWAfYqsGcmozoU31jSzjM9gxur.apk">Test App</a></p>
<p>Screenshots<br>
</p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/a/a50e2b5528346305bda57582bc9ced7dbdb4aadf.png" data-download-href="https://community.niotron.com/uploads/default/a50e2b5528346305bda57582bc9ced7dbdb4aadf" title="Screenshot_20210819-111223"><img src="https://community.niotron.com/uploads/default/optimized/2X/a/a50e2b5528346305bda57582bc9ced7dbdb4aadf_2_337x500.png" alt="Screenshot_20210819-111223" data-base62-sha1="ny98GHxJTqZwxzhNh7y3ox5VjvF" srcset="https://community.niotron.com/uploads/default/optimized/2X/a/a50e2b5528346305bda57582bc9ced7dbdb4aadf_2_337x500.png, https://community.niotron.com/uploads/default/optimized/2X/a/a50e2b5528346305bda57582bc9ced7dbdb4aadf_2_505x750.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/a/a50e2b5528346305bda57582bc9ced7dbdb4aadf_2_674x1000.png 2x" data-dominant-color="F6F1FE" style="aspect-ratio: 337 / 500;" loading="lazy" width="337" height="500"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">Screenshot_20210819-111223</span><span class="informations">800×1184 9.01 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p></p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/e/efae0cd1f16183834a0ea97a7ef797e3f6e2b150.png" data-download-href="https://community.niotron.com/uploads/default/efae0cd1f16183834a0ea97a7ef797e3f6e2b150" title="Screenshot_20210819-111238"><img src="https://community.niotron.com/uploads/default/optimized/2X/e/efae0cd1f16183834a0ea97a7ef797e3f6e2b150_2_252x375.png" alt="Screenshot_20210819-111238" data-base62-sha1="ycj0ZxMPxMweJ5uqIUUm4peRFPW" srcset="https://community.niotron.com/uploads/default/optimized/2X/e/efae0cd1f16183834a0ea97a7ef797e3f6e2b150_2_252x375.png, https://community.niotron.com/uploads/default/optimized/2X/e/efae0cd1f16183834a0ea97a7ef797e3f6e2b150_2_378x562.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/e/efae0cd1f16183834a0ea97a7ef797e3f6e2b150_2_504x750.png 2x" data-dominant-color="B7B2BF" style="aspect-ratio: 252 / 375;" loading="lazy" width="252" height="375"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">Screenshot_20210819-111238</span><span class="informations">800×1184 30.3 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>
</div></a></div><p></p>
<p></p><div class="lightbox-wrapper"><a class="lightbox" href="https://community.niotron.com/uploads/default/original/2X/5/583d7be17feb8a699bc33154c660b5764c575532.png" data-download-href="https://community.niotron.com/uploads/default/583d7be17feb8a699bc33154c660b5764c575532" title="Screenshot_20210819-111245"><img src="https://community.niotron.com/uploads/default/optimized/2X/5/583d7be17feb8a699bc33154c660b5764c575532_2_252x375.png" alt="Screenshot_20210819-111245" data-base62-sha1="cABKfSY4DxfBBF7dW7Q1nFWdiaC" srcset="https://community.niotron.com/uploads/default/optimized/2X/5/583d7be17feb8a699bc33154c660b5764c575532_2_252x375.png, https://community.niotron.com/uploads/default/optimized/2X/5/583d7be17feb8a699bc33154c660b5764c575532_2_378x562.png 1.5x, https://community.niotron.com/uploads/default/optimized/2X/5/583d7be17feb8a699bc33154c660b5764c575532_2_504x750.png 2x" data-dominant-color="B4AFBC" style="aspect-ratio: 252 / 375;" loading="lazy" width="252" height="375"><div class="meta">
<svg class="fa d-icon d-icon-far-image svg-icon" aria-hidden="true"><use href="#far-image"></use></svg><span class="filename">Screenshot_20210819-111245</span><span class="informations">800×1184 32.1 KB</span><svg class="fa d-icon d-icon-discourse-expand svg-icon" aria-hidden="true"><use href="#discourse-expand"></use></svg>