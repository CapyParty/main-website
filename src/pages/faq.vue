<template>
  <v-container class="fill-height d-flex justify-center">
    <v-main max-width="75%">
      <div class="text-center">
        <v-btn href="/" class="mb-5">
          <v-icon icon="mdi-home" size="large" start />
          Home
        </v-btn>
        <br />
        <v-expansion-panels>
          <v-expansion-panel>
            <v-expansion-panel-title>
              How do I install the mods on PC?
            </v-expansion-panel-title>
            <v-expansion-panel-text>
              <p>It's very easy!</p>
              <p>The following instructions were written for those who bought Jackbox on Steam but it should work for the Epic Games Store, Microsoft Store and Mac App Store versions!</p>
              <br /><p>Step 1.</p>
              <a href="https://main.capyparty.xyz/downloads">Go to our downloads page and choose which mod you want to download!</a>
              <p>(Make sure to click "Download for PC"!)</p>
              <br /><p>Step 2.</p>
              <p>Go to your Steam Library, right click on the game you downloaded the mod for, go to "Manage" and then click "Browse Local Files".</p>
              <div class="d-flex justify-center">
                <v-img
                  :height="200"
                  src="@/assets/faq/step2.png"
                ></v-img>
              </div>
              <br /><p>Step 3.</p>
              <p>Using whatever unarchiver you have (7-Zip, Ark, Windows Explorer, Finder) extract the contents of the folder into your game's local files.</p>
              <div class="d-flex justify-center">
                <v-img
                  :height="200"
                  src="@/assets/faq/step3.png"
                ></v-img>
              </div>
              <br /><p>Step 4.</p>
              <p>Start the game up and enjoy playing the mod!</p>
            </v-expansion-panel-text>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-title>
              How do I install the mods on Switch?
            </v-expansion-panel-title>
            <v-expansion-panel-text>
              <p>The written guide is currently in progress. Sorry!</p>
            </v-expansion-panel-text>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-title>
              How do I install the mods on Xbox/PlayStation/Android/other unsupported platforms?
            </v-expansion-panel-title>
            <v-expansion-panel-text>
              <p>We are planning on adding support for Android soon. However, we have no plans for PlayStation 4 or Xbox One since it's hard to acquire a softmodded one for now.</p>
              <p>If you do end up getting one yourself and you find a way to install mods on those platforms, let us know!</p>
            </v-expansion-panel-text>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-title>
              Would this break my game?
            </v-expansion-panel-title>
            <v-expansion-panel-text>
              <p>No! You can always rollback by uninstalling the game or running a file integrity check inside the marketplace you bought the game from (if installed on PC) or removing the "romfs.bin" file from the "atmosphere/contents" folder! (if installed on Switch)</p>
            </v-expansion-panel-text>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-title>
              Will I get banned? (Switch only)
            </v-expansion-panel-title>
            <v-expansion-panel-text>
              <p>We haven't gotten any reports of banned Switches due to our mods, but the risk is still there as just with any other homebrew on the Switch.</p>
              <p>But modified the code to not connect to Nintendo's servers to allow banned users/consoles and users with blocked Nintendo servers to play.</p>
              <a href="https://switch.hacks.guide/faq/#is-it-safe-to-use-homebrew-will-i-get-banned">More information can be found here.</a>
            </v-expansion-panel-text>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-title>
              Why do I have to join with capyparty.xyz and not jackbox.tv?
            </v-expansion-panel-title>
            <v-expansion-panel-text>
              <p>The main reasons are that capyparty.xyz is maintained by us and will not suddenly break because of a change Jackbox Games can submit any time.</p>
              <p>And for some mods like Cursed Points, you would be missing on gameplay features by using the original website. (For example, you won't see the "right" images on your controller)</p>
            </v-expansion-panel-text>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-title>
              Can I join the CapyParty team?
            </v-expansion-panel-title>
            <v-expansion-panel-text>
              <p>We are happy to let people who can draw, code or compose music to help us with our mods!</p>
              <a href="https://discord.gg/v7Xzqjg5KQ">Reach out to us on our Discord!</a>
            </v-expansion-panel-text>
          </v-expansion-panel>
        </v-expansion-panels>
      </div>
    </v-main>
  </v-container>
</template>

<script setup>
  //
</script>
