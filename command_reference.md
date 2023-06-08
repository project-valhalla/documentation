## Variables

<details>
  <summary>Engine</summary>
  
| Variable                 | Type               | Min | Default | Max     | Description |
| -------------------------|--------------------|-----|---------|---------|-------------|
| aaenvmap                 | Persistent integer | 0   | 1       | 1       |
| allfaces                 | Integer            | 0   | 0       | 1       | Allows texturing commands to apply the new texture to all the sides of the selected geometry.
| amd_eal_bug              | Integer            | 0   | 0       | 1       |
| amd_pf_bug               | Integer            | 0   | 0       | 1       |
|animationinterpolationtime| Integer            | 0   |  200    |  1000   |
| aodepthformat            | Integer            | 1   | 0       | 0       |
| aoderiv                  | Integer            | -1  | 1       | 1       |
| attachradius             | Integer            | 1   | 100     | 1000    |
| avatarfov                | Integer            | 10  | 40      | 100     | Field of view of the avatar (first person weapon).
| avatarzoomfov            | Integer            | 10  | 25      | 60      | Field of view of the avatar (first person weapon) while zoomed in. Currently read-only.
| batchdecals              | Integer            | 0   |  1      |  1      |
| batchgeom                | Integer            | 0   |  1      |  1      |
| clampsky                 | Integer            | 0   |  1      |  1      |
| compresspng              | Persistent integer | 0   | 9       | 9       |
| compresstga              | Persistent integer | 0   | 1       | 1       |
| connectname              | Persistent string  | N/A | N/A     | N/A     |
| csmcull                  | Integer            | 0   |  1      |  1      |
| csmfarplane              | Integer            | 64  |  1024   |  16384  |
| csminoq                  | Integer            | 0   |  1      |  1      |
| csmnearplane             | Integer            | 1   |  1      |  16     |
| cullparticles            | Integer            | 0   |  1      |  1      |
| dbgalias                 | Integer            | 0   | 4       | 1000    |
| dbgcolmesh               | Integer            | 0   | 0       | 1       |
| dbgdds                   | Integer            | 0   |  0      |  1      |
| dbgexts                  | Integer            | 0   | 0       | 1       |
| dbggrass                 | Integer            | 0   | 0       | 1       |
| dbgmodes                 | Integer            | 0   | 0       | 1       |
| dbgmovie                 | Integer            | 0   | 0       | 1       |
| dbgpcull                 | Integer            | 0   |  0      |  1      |
| dbgpseed                 | Integer            | 0   |  0      |  1      |
| dbgshader                | Integer            | 0   |  1      |  2      |
| dbgsound                 | Integer            | 0   |  0      |  1      |
| dbgstain                 | Integer            | 0   |  0      |  1      |
| dbgubo                   | Integer            | 0   |  0      |  1      |
| dbgvars                  | Integer            | 0   | 0       | 1       |
| debugao                  | Integer            | 0   | 0       | 1       | 
| debugbloom               | Integer            | 0   | 0       | 1       |
| debugdepth               | Integer            | 0   | 0       | 1       |
| debuglightscissor        | Integer            | 0   |  0      |  1      |
| debugrefract             | Integer            | 0   | 0       | 1       |
| debugrh                  | Integer            | -1  | 0       | RH_MAXSPLITS*(RH_MAXGRID + 2) |
| debugrsm                 | Integer            | 0   | 0       | 2       |
| debugshadowatlas         | Integer            | 0   | 0       |  3      |
| debugsmaa                | Integer            | 0   | 0       | 5       |
| debugstencil             | Integer            | 0   | 0       | 0xFF    |
| debugtqaa                | Integer            | 0   | 0       | 2       |
| defershaders             | Integer            | 0   |  1      |  1      |
| depthfaillights          | Integer            | 0   |  1      |  1      |
| depthtestlights          | Integer            | 0   |  2      |  2      |
| desktoph                 | Integer            | 1   | 0       | 0       |
| desktopw                 | Integer            | 1   | 0       | 0       |
| dtoutline                | Integer            | 0   |  1      |  1      |
| editcursor               | Integer            | 0   | 1       | 1       |
| editing                  | Integer            | 1   | 0       | 0       |
| entautoviewdist          | Integer            | 0   | 25      | 100     |
| entcamdir                | Persistent integer | 0   | 1       | 1       |
| entdrop                  | Integer            | 0   | 2       | 3       |
| entitysurf               | Integer            | 0   | 0       | 1       |
| entmovingshadow          | Integer            | 0   | 1       | 1       |
| entselradius             | Integer            | 0   | 2       | 10      |
| entselsnap               | Integer            | 0   | 0       | 1       |
| envmapbb                 | Integer            | 0   | 0       | 1       |
| envmapradius             | Integer            | 0   | 128     | 10000   |
| flarecutoff              | Persistent integer | 0   | 1000    | 10000   |
| flaresize                | Persistent integer | 20  | 100     | 500     |
| floatspeed               | Integer            | 1   | 100     | 10000   |
| fogoverlay               | Integer            | 0   | 1       | 1       |
| forcespotlights          | Integer            | 1   |  0      |  0      |
| frametimer               | Integer            | 0   | 0       | 1       |
| fullbright               | Integer            | 0   | 0       | 1       |
| fullbrightlevel          | Integer            | 0   | 160     | 255     |
| fullbrightmodels         | Persistent integer | 0   | 0       | 200     | 
| gcolorclear              | Integer            | 0   |  1      |  1      |
| gdepthclear              | Integer            | 0   |  1      |  1      |
| gdepthformat             | Integer            | 1   | 0       | 0       |
| ghasstencil              | Integer            | 1   | 0       | 0       |
| glcompat                 | Integer            | 1   | 0       | 0       |
| glerr                    | Integer            | 0   | 0       | 1       |
| glslversion              | Integer            | 1   | 0       | 0       |
| glversion                | Integer            | 1   | 0       | 0       |
| gpuskel                  | Persistent integer | 0   | 0       | 1       |
| gridlookup               | Integer            | 0   | 0       | 1       |
| hdraccummillis           | Integer            | 1   | 33      | 1000    |
| hdrreduce                | Integer            | 0   | 2       | 2       |
| hidechanges              | Integer            | 0   | 0       | 1       |
| hidehud                  | Integer            | 0   | 0       | 1       |
| hidestats                | Integer            | 0   | 0       | 1       |
| hwcubetexsize            | Integer            | 1   |  0      |  0      |
| hwmaxaniso               | Integer            | 1   |  0      |  0      |
| hwtexsize                | Integer            | 1   |  0      |  0      |
| hwtexunits               | Integer            | 1   |  0      |  0      |
| hwvtexunits              | Integer            | 1   |  0      |  0      |
| intel_mapbufferrange_bug | Integer            | 0   | 0       | 1       |
| intel_texalpha_bug       | Integer            | 0   | 0       | 1       |
| invalidcubeguard         | Integer            | 0   | 1       | 1       |
| lastdisconnectreason     | Read-only string   | N/A | N/A     | N/A     |
| lightpassesused          | Integer            | 1   |  0      |  0      |
| lightsoccluded           | Integer            | 1   |  0      |  0      |
| lightsvisible            | Integer            | 1   |  0      |  0      |
| lighttilealignh          | Integer            | 1   |  16     |  256    |
| lighttilealignw          | Integer            | 1   |  16     |  256    |
| lnblendpower             | Floating point     | 0   | 6.0f    | 1000    |
| lnjittermillis           | Integer            | 0   | 100     | 1000    |
| lnjitterradius           | Integer            | 0   | 3       | 100     |
| lnjitterscale            | Floating point     | 0   | 0.2f    | 10      |
| lnscrollmillis           | Integer            | 1   | 250     | 5000    |
| lnscrollscale            | Floating point     | 0   | 0.05f   | 10      |
| mainmenu                 | Read-only Integer  | 1   | 1       | 0       |
| mapmusic                 | String             | N/A | N/A     | N/A     | Music track of a map. Each time we load a map, this variable is updated with the current map's music track (if available).
| maptitle                 | String             | N/A | "Untitled Map by Unknown" | N/A | Title of a map. Each time we load a map, this variable is updated with the current map's title (if available).
| mastermotd               | String             | N/A | N/A     | N/A     |
| maxdrawbufs              | Integer            | 1   | 0       | 0       |
| maxdualdrawbufs          | Integer            | 1   | 0       | 0       |
| maxfsuniforms            | Integer            | 1   |  0      |  0      |
| maxgrass                 | Integer            | 10  | 10000   | 10000   |
| maxmerge                 | Integer            | 0   | 6       | 12      |
| maxmodelradiusdistance   | Integer            | 10  |  200    |  1000   |
| maxpvsblocker            | Integer            | 1   | 512     | 1<<16   |
| maxskelanimdata          | Integer            | 1   | 192     | 0       |
| maxtexoffset             | Integer            | 1   |  0      |  0      |
| maxtexrectoffset         | Integer            | 1   |  0      |  0      |
| maxvsuniforms            | Integer            | 1   |  0      |  0      |
| mesa_swap_bug            | Integer            | 0   | 0       | 1       |
| mesa_texrectoffset_bug   | Integer            | 0   | 0       | 1       |
| minface                  | Integer            | 0   | 4       | 12      |
| mintexoffset             | Integer            | 1   |  0      |  0      |
| mintexrectoffset         | Integer            | 1   |  0      |  0      |
| mipvis                   | Integer            | 0   | 0       | 1       |
| modelpreviewfov          | Integer            | 10  | 20      | 100     |
| modelpreviewpitch        | Integer            | -90 | -15     | 90      |
| movieaccelblit           | Integer            | 0   | 0       | 1       |
| movieaccelyuv            | Integer            | 0   | 1       | 1       |
| moviedir                 | Persistent string  | N/A | "movie" | N/A     | Similarly to `screenshotdir`, directory to which movies are saved.
| msaadepthblit            | Integer            | 0   | 0       | 1       |
| msaalight                | Integer            | 1   | 0       | 0       |
| msaamaxcolortexsamples   | Integer            | 1   | 0       | 0       |
| msaamaxdepthtexsamples   | Integer            | 1   | 0       | 0       | 
| msaamaxsamples           | Integer            | 1   | 0       | 0       |
| msaaminsamples           | Integer            | 1   | 0       | 0       |
| msaasamples              | Integer            | 1   | 0       | 0       |
| numcpus                  | Integer            | 1   | 1       | 16      |
| numoctaents              | Integer            | 1   | 0       | 0       |
| octaentsize              | Integer            | 0   | 64      | 1024    |
| oqdist                   | Integer            | 0   |  256    |  1024   |
| oqdynent                 | Integer            | 0   |  1      |  1      |
| oqfrags                  | Integer            | 0   |  8      |  64     |
| oqgeom                   | Integer            | 0   |  1      |  1      |
| oqlights                 | Integer            | 0   |  1      |  1      |
| oqmm                     | Integer            | 0   |  4      |  8      |
| oqvol                    | Integer            | 0   |  1      |  1      |
| oqwait                   | Integer            | 0   |  1      |  1      |
| outline                  | Integer            | 0   |  0      |  1      |
| paintblendmapdelay       | Integer            | 1   | 500     | 3000    |
| paintblendmapinterval    | Integer            | 1   | 30      | 3000    |
| passthroughcube          | Integer            | 0   | 1       | 1       |
| passthroughent           | Integer            | 0   | 1       | 1       |
| passthroughsel           | Integer            | 0   | 0       | 1       |
| physinterp               | Integer            | 0   | 1       | 1       |
| printvbo                 | Integer            | 0   | 0       | 1       |
| progressbackground       | Integer            | 0   | 0       | 1       |
| pvsleafsize              | Integer            | 1   | 64      | 1024    |
| ragdollairfric           | Floating point     | 0   | 0.996f  | 1       | 
| ragdollbodyfric          | Floating point     | 0   | 0.95f   | 1       |
| ragdollbodyfricscale     | Floating point     | 0   | 2       | 10      |
| ragdollconstrain         | Integer            | 1   | 7       | 100     |
| ragdollexpireoffset      | Integer            | 0   | 2500    | 30000   |
| ragdolleyesmooth         | Floating point     | 0   | 0       | 1       |
| ragdolleyesmoothmillis   | Integer            | 1   | 1       | 10000   |
| ragdollgravity           | Floating point     | 0   | 198.0f  | 200     |
| ragdollgroundfric        | Floating point     | 0   | 0.8f    | 1       |
| ragdollrotfric           | Floating point     | 0   | 0.85f   | 1       |
| ragdollrotfricstop       | Floating point     | 0   | 0.1f    | 1       |
| ragdolltimestepmax       | Integer            | 1   | 10      | 50      |
| ragdolltimestepmin       | Integer            | 1   | 5       | 50      |
| ragdollunstick           | Floating point     | 0   | 10      | 1e3f    |
| ragdollwaterexpireoffset | Integer            | 0   | 4000    | 30000   |
| ragdollwaterfric         | Floating point     | 0   | 0.85f   | 1       |
| replayparticles          | Integer            | 0   |  1      |  1      |
| rhclipgrid               | Integer            | 0   | 1       | 1       |
| rhdynmm                  | Integer            | 0   | 0       | 1       |
| rhdyntex                 | Integer            | 0   | 0       | 1       |
| rhinoq                   | Integer            | 0   |  1      |  1      |
| rsmcull                  | Integer            | 0   | 1       | 1       |
| savebak                  | Persistent integer | 0   | 2       | 2       | Controls whether `.bak` files (backups) of the map we are editing are saved at each map save (`/savemap`).
| scaledds                 | Integer            | 0   |  2      |  4      |
| screenshotdir            | Persistent string  | N/A | "screenshot" | N/A| Directory to which screenshots are saved (`*/screenshot`).
| screenshotformat         | Persistent integer | 0   | IMG_PNG | NUMIMG-1| 
| screenshotquality        | Persistent integer | 0   | 97      | 100     |
| sdl_xgrab_bug            | Integer            | 0   | 0       | 1       |
| selectcorners            | Integer            | 0   | 0       | 1       |
| selectionsurf            | Integer            | 0   | 0       | 1       |
| serverip                 | String             | N/A | N/A     | N/A     |
| serveruprate             | Integer            | 0   |  0      |2147483647|
| showentradius            | Integer            | 0   | 1       | 1       |
| showsky                  | Integer            | 0   |  1      |  1      |
| smaa4x                   | Integer            | 1   | 0       | 0       |
| smaas2x                  | Integer            | 1   | 0       | 0       |
| smaat2x                  | Integer            | 1   | 0       | 0       |
| smbbcull                 | Integer            | 0   |  1      |  1      |
| smborder                 | Integer            | 0   |  3      |  16     |
| smborder2                | Integer            | 0   |  4      |  16     |
| smdistcull               | Integer            | 0   |  1      |  1      |
| smdynshadow              | Integer            | 0   |  1      |  1      |
| sminoq                   | Integer            | 0   |  1      |  1      |
| smmaxsize                | Integer            | 1   |  384    |  1024   |
| smminradius              | Integer            | 0   |  16     |  10000  |
| smminsize                | Integer            | 1   |  96     |  1024   |
| smnodraw                 | Integer            | 0   |  0      |  1      |
| smnoshadow               | Integer            | 0   |  0      |  1      |
| smquery                  | Integer            | 0   |  1      |  1      |
| smsidecull               | Integer            | 0   |  1      |  1      |
| smused                   | Integer            | 1   |  0      |  0      |
| smviscull                | Integer            | 0   |  1      |  1      |
| softexplosion            | Persistent integer | 0   | 0       | 1       |
| softexplosionblend       | Integer            | 1   | 16      | 64      |
| statrate                 | Integer            | 1   | 200     | 1000    |
| stereo                   | Integer            | 0   |  1      |  1      |
| testtags                 | Integer            | 0   | 0       | 1       |
| testtricol               | Integer            | 0   | 0       | 2       |
| textinputfilter          | Integer            | 0   | 5       | 1000    |
| thirdperson              | Integer            | 0   | 0       | 2       |
| tqaaresolvegather        | Integer            | 1   | 0       | 0       |
| usedds                   | Integer            | 0   |  1      |  1      |
| usetexcompress           | Integer            | 1   | 0       | 0       |
| usetexgather             | Integer            | 1   | 0       | 0       |
| useubo                   | Integer            | 1   | 0       | 0       |
| usevdelta                | Integer            | 1   | 0       | 0       |
| volderiv                 | Integer            | -1  |  1      |  1      |
| waterlod                 | Persistent integer | 0   | 1       | 3       |
| waterreflectstep         | Persistent integer | 1   | 32      | 10000   |
| watersubdiv              | Persistent integer | 0   | 2       | 3       |
| wireframe                | Integer            | 0   | 0       | 1       |
| zoom                     | Integer            | -1  | 0       | 1       |

</details>

<details>
  <summary>Game</summary>
  
| Variable            | Type               | Min | Default | Max         | Description |
| --------------------|--------------------|-----|---------|-------------|-------------|
| aidebug             | Integer            | 0   | 0       | 6           |
| aiforcegun          | Integer            | -1  | -1      | Max weapons |
| allycrosshair       | Persistent Integer | 0   | 1       | 1
| animoverride        | Integer            |-1   | 0       | Max animations
| autoauth            | Persistent integer | 0   | 1       | 1
| autoswitch          | Persistent integer | 0   | 1       | 1
| blood               | Persistent integer | 0   | 1       | 1
| chatsound           | Persistent integer | 0   | 1       | 1
| deadpush            | Persistent integer | 1   | 2       | 20
| deathfromabove      | Persistent integer | 0   | 1       | 1
| dropwaypoints       | Integer            | 0   | 1       | 1
| footstepssound      | Persistent integer | 0   | 1       | 1
| forceplayermodels   | Persistent integer | 0   | 0       | 1
| gore                | Persistent integer | 0   | 1       | 1
| goreeffect          | Persistent integer | N/A | N/A     | N/A
| hidedead            | Persistent integer | 0   | 0       | 1
| highlightscore      | Persistent integer | 0   | 1       | 1
| hitcrosshair        | Persistent integer | 0   | 400     | 1000
| hitsound            | Persistent integer | 0   | 0       | 2
| hudgun              | Persistent integer | 0   | 1       | 1
| hudgunsway          | Persistent integer | 0   | 1       | 1
| itemtrans           | Persistent integer | 0   | 1       | 1
| killsound           | Persistent integer | 0   | 1       | 2
| maxradarscale       | Persistent integer | 0   | 1024    | 10000
| minimapalpha        | Persistent float   | 0   | 1       | 1
| minradarscale       | Persistent integer | 0   | 384     | 10000
| muzzleflash         | Persistent integer | 0   | 1       | 1
| playercolor         | Persistent integer | 0   | 4       | Max colors
| playercolorblue     | Persistent integer | 0   | 0       | Max blue colors
| playercolorred      | Persistent integer | 0   | 0       | Max red colors
| playermodel         | Persistent integer | 0   | 0       | Max player models
| playersearch        | Persistent integer | 0   | 3       | 10
| playheadshotsound   | Persistent integer | 0   | 1       | 2
| radarteammates      | Persistent integer | 0   | 1       | 1
| ragdoll             | Persistent integer | 0   | 1       | 1
| ragdollfade         | Persistent integer | 0   | 400     | 5000
| ragdollmillis       | Persistent integer | 0   | 10000   | 300000
| regensound          | Persistent integer | 0   | 1       | 1
| showclientnum       | Persistent integer | 0   | 1       | 1
| showconnecting      | Persistent integer | 0   | 1       | 1
| showmodeinfo        | Persistent integer | 0   | 1       | 1
| showping            | Persistent integer | 0   | 1       | 1
| showpj              | Persistent integer | 0   | 1       | 1
| showservinfo        | Persistent integer | 0   | 1       | 1
| showspectators      | Persistent integer | 0   | 1       | 1
| showwaypoints       | Persistent integer | 0   | 1       | 1
| showwaypointsradius | Persistent integer | 0   | 200     | 10000
| smoothdist          | Persistent integer | 0   | 32      | 64
| smoothmove          | Persistent integer | 0   | 75      | 100
| specmode            | Integer            | 0   | 0       | 2
| swayrollfactor      | Floating point     | 1   | 3       | 30
| swayside            | Floating point     | 0   | 0.06f   | 1
| swaystep            | Floating point     | 1   | 39.2f   | 1
| swayup              | Floating point     | -1  | 0.11f   | 1
| teamcolortext       | Persistent integer | 0   | 1       | 1
| teleteam            | Integer            | 0   | 1       | 1
| testanims           | Integer            | 0   | 0       | 1
| testpitch           | Integer            | -90 | 0       | 90
  
</details>

<details>
  <summary>Server</summary>

| Variable             | Type                 | Min | Default             | Max        | Description|
| ---------------------|----------------------|-----|---------------------|------------|------------|
| adminpass            | String               | N/A | N/A                 | N/A        | Allows you to gain administrator privileges by `/setmaster password_here`.
| autorecorddemo       | Integer              | 0   | 0                   | 1          | Whether or not to enable server-side demo recording automatically for every match (0 = always, 1 = when requested).
| botnames             | String               | N/A | N/A                 | N/A        | Generates a list of the bot names used in a server.
| ctftkpenalty         | Integer              | 0   | 1                   | 1          | Whether or not teamkilling the flag runner in CTF should disallow the teamkiller from picking up the flag.
| demodir              | Persistent string    | N/A | N/A                 | N/A        | Sets the directory to which demos are saved.
| lockmaprotation      | Integer              | N/A | N/A                 | N/A        | Whether or not to allow players to vote on maps not in the rotation (0 = any vote, 1 = master votes only, 2 = administrator votes only).
| mastername           | String               | N/A | master.tesseract.gg | N/A        | Sets the master server address.
| masterport           | Integer              | 1   | 41999               | 0xFFFF     | Sets the master server port.
| maxclients           | Integer              | 0   | 8                   | 128        | Max players a server can accept.
| maxdupclients        | Integer              | 0   | 0                   | 128        | Maximum number of duplicate clients allowed on a server.
| maxdemos             | Integer              | 0   | 5                   | 25         | Max demos a server can store.
| maxdemosize          | Integer              | 0   | 16                  | 31         | Max size of a demo.
| modifiedmapspectator | Integer              | 0   | 1                   | 2          | Whether or not to automatically spectate players who are playing on a modified version of the current map.
| overtime             | Integer              | 0   | 1                   | 1          | Whether or not overtime is enabled for matches.
| persistteams         | Integer              | 0   | 1                   | 1          | Whether or not teams should persist across matches and avoid autobalancing.
| publicserver         | Integer              | 0   | 1                   | 2          | Level of freedom in the server: when set to 0, allows `/setmaster 1` and locked/private modes. When set to 1, can only gain master by `/auth` or administrator privileges, and does not allow locked/private modes. When set to 2, allows `/setmaster 1` but disallows private modes.
| restrictdemos        | Integer              | 0   | 1                   | 1          | Controls whether administrator privileges are necessary to record a demo.
| restrictgamespeed    | Integer              | 0   | 1                   | 1          | Controls whether master privileges are necessary to change game speed.
| restrictpausegame    | Integer              | 0   | 1                   | 1          | Controls whether master privileges are necessary to pause the current game.
| serverauth           | String               | N/A | N/A                 | N/A        | Domain to use for local authkeys to the server so people can authenticate by `/auth domain_here`; the string must not be empty and should be unique to your server.
| serverbotbalance     | Integer              | 0   | 1                   | 1          | Enables automatic team balancing for bots if 1 and disables it if 0. Only privileged or local players can use this command.
| serverbotlimit       | Integer              | 0   | 8                   | 32         | Max number of bots a server can accept.
| serverip             | String               | N/A | N/A                 | N/A        | Sets the server IP.
| servermotd           | String               | N/A | N/A                 | N/A        | Optional console message to send to players on connect.
| servername           | String               | N/A | N/A                 | N/A        | Name of the server which is primarily displayed on the server browser. In Tesseract this variable is `serverdesc`.
| serverpass           | String               | N/A | N/A                 | N/A        | Optional password required to connect to the server.
| serverport           | Integer              | 0   | 4200                | 0xFFFF     | Specifies the port the server we are hosting should bind/listen to.
| serveruprate         | Integer              | 0   | 0                   | 2147483647 |
| spectatorchat        | Integer              | 0   | 0                   | 1          | Whether or not chat messages sent by spectators should be visible to players. When 0, spectators are allowed to chat with players (default); when 1, spectators are only allowed to chat with other spectators.
| updatemaster         | Integer              | 0   | 1                   | 1          | Toggles whether or not the server should report to the master server.

</details>

## Commands

<details>
  <summary>Engine</summary>
  Coming soon™
</details>

<details>
  <summary>Game</summary>

| Command                 | Arguments  | Description
| ------------------------|------------|---------------------
| allowthirdperson        | N/A        | Command that returns a boolean value: 1 if `thirdperson` is allowed, 0 if not.
| auth                    |
| authkey                 |
| authkick                |
| botadd                  | 1          | Adds a bot with a random player model and name and the skill specified by the first argument.
| botbalance              |
| botdel                  | N/A        | Kicks the most recent bot that was added.
| botlimit                |            |
| checkmaps               |            |
| clearbans               | N/A        | Clears every ban that has been issued. Bans are automatically cleared when a server is empty.
| cleardemos              | N/A        | Clears all demos saved in a server.
| clearwaypoints          | N/A        | Clears all waypoints without needing to reload a map.
| clearwpcache            |            | Clears waypoints cache.
| cycleweapon             |            |
| dauth                   |            |
| dauthkick               |            |
| delselwaypoints         | N/A        | Clears waypoints inside grid selection.
| dropflag                | N/A        | Drops the flag we are holding in CTF modes.
| follow                  | N/A        |
| gamespeed               |            |
| genauthkey              |            |
| getaccuracy             |            |
| getclientammo           |            |
| getclientcolor          |            |
| getclientcolorname      |            |
| getclientdeaths         |            |
| getclientfrags          |            |
| getclienthealth         |            |
| getclientmaxhealth      |            |
| getclientmodel          |            |
| getclientname           |            |
| getclientnum            |            |
| getclientpowerup        |            |
| getclientpowerupmillis  |            |
| getclientprivilege      |            |
| getclientscore          |            |
| getclientshield         |            |
| getclientteam           |            |
| getclientweapon         |            |
| getdeaths               |            |
| getdemo                 |            |
| getflags                |            |
| getfollow               |            |
| getfrags                |            |
| getkillfeedactor        |            |
| getkillfeedcrit         |            |
| getkillfeedtarget       |            |
| getkillfeedweap         |            |
| getmap                  | N/A        | Downloads the map that is available on the server if it has been sent with `sendmap`. Only used in the map editor.
| getmastermode           |            |
| getmastermodename       |            |
| getmode                 |            |
| getmodename             |            |
| getmodeprettyname       |            |
| getmutators             |            |
| getmutdesc              |            |
| getname                 |            |
| getnextmode             |            |
| getnextmutators         |            |
| getplayercolor          |            |
| getscorelimit           |            |
| getservauth             |            |
| getservdesc             |            |
| getteam                 |            |
| getteamname             |            |
| getteamscore            |            |
| gettotaldamage          |            |
| gettotalshots           |            |
| getweapon               |            |
| goto                    |            |
| gotosel                 |            |
| hasauthkey              |            |
| hashpwd                 |            |
| ignore                  |            |
| intermission            | N/A        | Returns a boolean value: 1 if the game has ended (intermission), 0 if not.
| isadmin                 |            |
| isai                    |            |
| isauth                  |            |
| isdead                  |            |
| isignored               |            |
| islagged                |            |
| ismaster                |            |
| isspectator             |            |
| kick                    |            |
| listclients             |            |
| listdemos               |            |
| loadwaypoints           |            |
| loopscoreboard          |            |
| map                     |            |
| mastermode              |            |
| melee                   |            |
| mode                    |            |
| movewaypoints           |            |
| mutator                 |            |
| mute                    |            |
| name                    |            |
| nextfollow              |            |
| nextweapon              |            |
| numscoreboard           |            |
| paused                  |            |
| pausegame               |            |
| prettygamespeed         |            |
| primary                 | N/A        | Fires the primary fire of the selected weapon. In other Cube games, this command is usually replaced with `shoot`. If used when dead, the player is also respawned.
| recorddemo              |            |
| refreshscoreboard       |            |
| registertip             |            |
| respawn                 | N/A        | Respawns our client if the spawn delay has expired.
| sauth                   |            |
| sauthkick               |            |
| saveauthkeys            |            |
| savewaypoints           |            |
| say                     |            |
| sayteam                 |            |
| scoreboardhighlight     |            |
| scoreboardmap           |            |
| scoreboardmode          |            |
| scoreboardmultiplayer   |            |
| scoreboardping          |            |
| scoreboardpj            |            |
| scoreboardservinfo      |            |
| scoreboardshowclientnum |            |
| scoreboardshowfrags     |            |
| scoreboardstatus        |            |
| scoreboardtime          |            |
| secondary               | N/A        | Fires the secondary fire of the selected weapon. If used when dead, the player is also respawned.
| sendmap                 | N/A        | Sends the map to the server so that it can be downloaded with `getmap`.
| servcmd                 |            |
| servinfoicon            |            |
| servinfomastermode      |            |
| servinfomastermodename  |            |
| servinfomode            |            |
| servinfomodename        |            |
| servinfotime            |            |
| setmaster               |            |
| setteam                 |            |
| setweapon               |            |
| spectating              | N/A        | Returns a boolean value: 1 if our client is spectating, 0 if not.
| spectator               |            |
| stopdemo                |            |
| suicide                 | N/A        | Immediately kills our player.
| taunt                   | N/A        | Plays the current character's taunt animation and voice line if available.
| team                    |            |
| timeremaining           |            |
| unignore                |            |
| unmute                  |            |
| useitem                 |            |
| weapon                  |            |
| whisper                 |            |

</details>

<details>
  <summary>Server</summary>

| Command           | Arguments  | Description
| ------------------|------------|---------------------
| adduser           | 4          |
| clearipbans       | N/A        | Forgets about all of the issued IP bans.
| clearusers        | N/A        |
| ipban             | 1          | Issues an IP ban.
| maprotation       | 4          | Defines server's map rotation.
| maprotationreset  | N/A        | Resets map rotation in a server.
| startlistenserver | N/A        | Starts a listen server from within a running game client.
| stoplistenserver  | N/A        | Stops a listen server from within a running game client.
| teamkillkick      | 3          | Specifies the gamemode in which the teamkill limit is used, the maximum number of teamkills a player is allowed to commit and the duration of teamkill auto-kicks.
| teamkillkickreset | N/A        | Removes automatic kicks triggered by an excessive amount of teamkills (specified with `teamkillkick`).

</details>

## CubeScript Hooks

<details>
  <summary>Engine</summary>
  
| Name              | Description                                                                                              
| ------------------|----------------------------------------------------------------------------------------------------|
| resetgl           | Triggers when we apply settings changes and we need to reset OpenGL.                               |
| resetshaders      | Triggers when we apply settings changes and we need to reset the shaders.                          |
| resetsound        | Triggers when we apply settings changes and we need to reset audio.                                |

</details>

<details>
  <summary>Game</summary>
  
| Name              | Description                                                                                              
| ------------------|----------------------------------------------------------------------------------------------------|
| on_connect        | Triggers every time our client successfully connects to a server, being it local or not.           |
| on_death          | Triggers each time our client dies.                                                                |
| on_disconnect     | Triggers every time our client disconnects from a server, being it local or not.                   |
| on_edittoggle     | Triggers when we enter edit mode (originally `edittoggled`).                                       |
| on_intermission   | Triggers when a game ends and intermission starts (originally `intermission`).                     |
| on_kill           | Triggers when our client kills another.                                                            |
| on_killfeed       | Triggers each time a player dies.                                                                  |
| on_mainmenutoggle | Triggers when the main menu is opened (usually by pressing "ESC") (originally `mainmenutoggled`).  |
| on_mapstart       | Triggers when a map has finished loading (originally `mapstart`).                                  |
| on_spawn          | Triggers when our client spawns.                                                                   |
| on_suicide        | Triggers each time we kill our own player.                                                         |
| on_teamkill       | Triggers each time we kill an ally.                                                                |

</details>
