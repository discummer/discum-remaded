Table of Contents
=================

-   [Get Started](using/Get_Started.md)
    -   [installing discum](using/Get_Started.md#installing)
    -   [client initialization](using/Get_Started.md#initializing-your-client)
    -   [some examples](using/Get_Started.md#examples)
-   [General Functions and Variables](using/General.md)
    -   [logging](using/General.md#logging)
    -   [general variables](using/General.md#general-variables)
    -   [gateway variables](using/General.md#gateway-variables)
        -   [session settings/data](using/General.md#botgatewaysession)
    -   [check token](using/General.md#checktoken)
    -   [switch account/token](using/General.md#switchAccount)
    -   [switch proxy](using/General.md#switchProxy)
    -   [convert between snowflake and unixts](using/General.md#snowflake_to_unixts-and-unixts_to_snowflake)
    -   [gateway functions](using/General.md#gateway-functions)
        - [add functions to gateway command list](using/General.md#gatewaycommand)
        - [remove functions from gateway command list](using/General.md#gatewayremoveCommand)
        - [clear gateway command list](using/General.md#gatewayclearCommands)
        - [connect to the gateway](using/General.md#gatewayrun)
        - [reset gateway session](using/General.md#gatewayresetSession)
        - [send payload to gateway](using/General.md#gatewaysend)
        - [auto parse gateway responses](using/General.md#respparsedauto)
        - [event checking](using/events.md)

-   Start
    -   [request discord build number](using/REST_Actions.md#getbuildnumber)
    -   [calculate superproperties](using/REST_Actions.md#getsuperproperties)
    -   [get xfingerprint](using/REST_Actions.md#getxfingerprint)
    -   [login](using/REST_Actions.md#login)
    -   [{remote auth gateway} initialize bot.ra](using/Remote_Authentication.md#initRA)
    -   [{remote auth gateway} login using remote authentication](using/Remote_Authentication.md#remoteAuthLogin)
    -   [get gateway url](using/REST_Actions.md#getgatewayurl)
    -   [get status of discord's servers](using/REST_Actions.md#getdiscordstatus)
    -   [get "detectables"](using/REST_Actions.md#getdetectables)
    -   [get OAuth2 tokens](using/REST_Actions.md#getoauth2tokens)
    -   [get hash of stable discord version](using/REST_Actions.md#getversionstablehash)
    -   [get user library](using/REST_Actions.md#getLibrary)
    -   [get bad domain hashes](using/REST_Actions.md#getBadDomainHashes)
    -   [{gateway} parse READY](using/Gateway_Actions.md#respparsedready)
    -   [{gateway} parse READY\_SUPPLEMENTAL](using/Gateway_Actions.md#respparsedready_supplemental)
-   User
    -   [get relationships](using/REST_Actions.md#getrelationships)
    -   [get mutual friends](using/REST_Actions.md#getMutualFriends)
    -   [{risky action} send friend request](using/REST_Actions.md#requestfriend)
    -   [accept friend request](using/REST_Actions.md#acceptfriend)
    -   [unfriend/unblock/remove friend request/reject friend request](using/REST_Actions.md#removerelationship)
    -   [block user](using/REST_Actions.md#blockuser)
    -   [get user profile](using/REST_Actions.md#getprofile)
    -   [get client info](using/REST_Actions.md#info)
    -   [get user affinities](using/REST_Actions.md#getuseraffinities)
    -   [get guild affinities](using/REST_Actions.md#getguildaffinities)
    -   [get mentions from inbox](using/REST_Actions.md#getmentions)
    -   [remove mention from inbox](using/REST_Actions.md#removementionfrominbox)
    -   [get my stickers](using/REST_Actions.md#getmystickers)
    -   [get user notes](using/REST_Actions.md#getnotes)
    -   [set user note](using/REST_Actions.md#setUserNote)
    -   [get RTC regions](using/REST_Actions.md#getrtcregions)
    -   [get voice regions](using/REST_Actions.md#getVoiceRegions)
    -   [change username](using/REST_Actions.md#setusername)
    -   [change email](using/REST_Actions.md#setemail)
    -   [change password](using/REST_Actions.md#setpassword)
    -   [change discriminator](using/REST_Actions.md#setdiscriminator)
    -   [{risky action} change avatar](using/REST_Actions.md#setavatar)
    -   [change profile color](using/REST_Actions.md#setProfileColor)
    -   [change "about me" bio](using/REST_Actions.md#setAboutMe)
    -   [change profile banner](using/REST_Actions.md#setBanner)
    -   [get Time-based One Time Password (TOTP) url](using/REST_Actions.md#gettotpurl)
    -   [calculate Time-based One Time Password (TOTP) code](using/REST_Actions.md#calculatetotpcode)
    -   [enable 2FA](using/REST_Actions.md#enable2fa)
    -   [disable 2FA](using/REST_Actions.md#disable2fa)
    -   [get 2FA backup codes](using/REST_Actions.md#getbackupcodes)
    -   [disable account](using/REST_Actions.md#disableaccount)
    -   [delete account](using/REST_Actions.md#deleteaccount)
    -   [set phone number](using/REST_Actions.md#setphone)
    -   [validate phone number](using/REST_Actions.md#validatephone)
    -   [set DM scan level](using/REST_Actions.md#setdmscanlvl)
    -   [allow DMs from guild members](using/REST_Actions.md#allowdmsfromservermembers)
    -   [allow friend requests from...](using/REST_Actions.md#allowfriendrequestsfrom)
    -   [discord analytics consent](using/REST_Actions.md#analyticsconsent)
    -   [allow discord to track screen reader usage](using/REST_Actions.md#allowScreenReaderTracking)
    -   [request my (science/tracking) data](using/REST_Actions.md#requestMyData)
    -   [get connected accounts](using/REST_Actions.md#getconnectedaccounts)
    -   [get url to connect account](using/REST_Actions.md#getConnectionUrl)
    -   [display connection on profile](using/REST_Actions.md#enableConnectionDisplayOnProfile)
    -   [display connection on status](using/REST_Actions.md#enableConnectionDisplayOnStatus)
    -   [remove connection](using/REST_Actions.md#removeConnection)
    -   [get billing history](using/REST_Actions.md#getbillinghistory)
    -   [get payment sources](using/REST_Actions.md#getpaymentsources)
    -   [get billing subscriptions](using/REST_Actions.md#getbillingsubscriptions)
    -   [get stripe client secret](using/REST_Actions.md#getstripeclientsecret)
    -   [set theme (light/dark)](using/REST_Actions.md#settheme)
    -   [set msg display (cozy/compact)](using/REST_Actions.md#setmessagedisplay)
    -   [enable gif autoplay](using/REST_Actions.md#enablegifautoplay)
    -   [enable animated emoji](using/REST_Actions.md#enableanimatedemoji)
    -   [set sticker animation config](using/REST_Actions.md#setstickeranimation)
    -   [enable text-to-speech (tts)](using/REST_Actions.md#enabletts)
    -   [enable inline media](using/REST_Actions.md#enableLinkedImageDisplay)
    -   [enable large image preview](using/REST_Actions.md#enableImageDisplay)
    -   [enable link preview](using/REST_Actions.md#enablelinkpreview)
    -   [enable reaction rendering](using/REST_Actions.md#enablereactionrendering)
    -   [enable emoticon conversion](using/REST_Actions.md#enableemoticonconversion)
    -   [set AFK timeout](using/REST_Actions.md#setafktimeout)
    -   [set locale](using/REST_Actions.md#setlocale)
    -   [enable dev mode](using/REST_Actions.md#enabledevmode)
    -   [activate application test mode](using/REST_Actions.md#activateapplicationtestmode)
    -   [get application data](using/REST_Actions.md#getapplicationdata)
    -   [enable activity display](using/REST_Actions.md#enableactivitydisplay)
    -   [set hypesquad](using/REST_Actions.md#sethypesquad)
    -   [leave hypesquad](using/REST_Actions.md#leavehypesquad)
    -   [get build overrides](using/REST_Actions.md#getBuildOverrides)
    -   [enable source maps](using/REST_Actions.md#enableSourceMaps)
    -   [suppress guild everyone pings](using/REST_Actions.md#suppressEveryonePings)
    -   [suppress guild role mentions](using/REST_Actions.md#suppressRoleMentions)
    -   [enable guild mobile push notifications](using/REST_Actions.md#enableMobilePushNotifications)
    -   [set guild channel message notification overrides](using/REST_Actions.md#setChannelNotificationOverrides)
    -   [set guild message notifications](using/REST_Actions.md#setMessageNotifications)
    -   [mute guild](using/REST_Actions.md#muteGuild)
    -   [mute DM](using/REST_Actions.md#muteDM)
    -   [set thread notifications](using/REST_Actions.md#setThreadNotifications)
    -   [get spam report menu info](using/REST_Actions.md#getReportMenu)
    -   [report spam](using/REST_Actions.md#reportSpam)
    -   [get handoff token](using/REST_Actions.md#getHandoffToken)
    -   [invite someone to a call](using/REST_Actions.md#inviteToCall)
    -   [decline an incoming call](using/REST_Actions.md#declineCall)
    -   [logout](using/REST_Actions.md#logout)
    -   [{gateway} set status](using/Gateway_Actions.md#gatewaysetstatus)
    -   [{gateway} set custom status](using/Gateway_Actions.md#gatewaysetcustomstatus)
    -   [{gateway} set playing status](using/Gateway_Actions.md#gatewaysetplayingstatus)
    -   [{gateway} set streaming status](using/Gateway_Actions.md#gatewaysetstreamingstatus)
    -   [{gateway} set listening status](using/Gateway_Actions.md#gatewaysetlisteningstatus)
    -   [{gateway} set watching status](using/Gateway_Actions.md#gatewaysetwatchingstatus)
    -   [{gateway} remove playing status](using/Gateway_Actions.md#gatewayremoveplayingstatus)
    -   [{gateway} remove streaming status](using/Gateway_Actions.md#gatewayremovestreamingstatus)
    -   [{gateway} remove listening status](using/Gateway_Actions.md#gatewayremovelisteningstatus)
    -   [{gateway} remove watching status](using/Gateway_Actions.md#gatewayremovewatchingstatus)
    -   [{gateway} clear activities](using/Gateway_Actions.md#gatewayclearactivities)
    -   [{gateway} parse SESSIONS\_REPLACE event](using/Gateway_Actions.md#gatewayparsesessions_replace)
-   [Science/Analytics](using/REST_Actions.md#scienceanalytics)
    -   [send science requests](using/REST_Actions.md#science)
    -   [calculate client UUID](using/REST_Actions.md#calculateclientuuid)
    -   [refresh client UUID](using/REST_Actions.md#refreshclientuuid)
    -   [parse client UUID](using/REST_Actions.md#parseclientuuid)
-   Guild
    -   [get info from invite code](using/REST_Actions.md#getinfofrominvitecode)
    -   [{risky action} join guild](using/REST_Actions.md#joinguild)
    -   [preview/lurk-in guild](using/REST_Actions.md#previewGuild)
    -   [leave guild](using/REST_Actions.md#leaveguild)
    -   [create invite code](using/REST_Actions.md#createinvite)
    -   [get guild invites](using/REST_Actions.md#getGuildInvites)
    -   [get my guilds (get guilds)](using/REST_Actions.md#getGuilds)
    -   [get channels in a guild](using/REST_Actions.md#getGuildChannels)
    -   [get roles in a guild](using/REST_Actions.md#getGuildRoles)
    -   [get discoverable guilds](using/REST_Actions.md#getDiscoverableGuilds)
    -   [get guild regions](using/REST_Actions.md#getGuildRegions)
    -   [create guild](using/REST_Actions.md#createGuild)
    -   [delete guild](using/REST_Actions.md#deleteGuild)
    -   [kick user](using/REST_Actions.md#kick)
    -   [ban user](using/REST_Actions.md#ban)
    -   [revoke ban](using/REST_Actions.md#revokeban)
    -   [get role member counts](using/REST_Actions.md#getRoleMemberCounts)
    -   [get guild integrations](using/REST_Actions.md#getGuildIntegrations)
    -   [get templates](using/REST_Actions.md#getGuildTemplates)
    -   [get members that have a certain role](using/REST_Actions.md#getRoleMemberIDs)
    -   [set the role of multiple members at the same time](using/REST_Actions.md#addMembersToRole)
    -   [set roles of a member](using/REST_Actions.md#setMemberRoles)
    -   [get guild verification form](using/REST_Actions.md#getmemberverificationdata)
    -   [agree to guild rules](using/REST_Actions.md#agreeguildrules)
	-   [create thread](using/REST_Actions.md#createthread)
    -   [leave thread](using/REST_Actions.md#leavethread)
    -   [join thread](using/REST_Actions.md#jointhread)
    -   [archive thread](using/REST_Actions.md#archiveThread)
    -   [unarchive thread](using/REST_Actions.md#unarchiveThread)
    -   [search for school hubs](using/REST_Actions.md#lookupSchool)
    -   [signup for school hub waiting list](using/REST_Actions.md#schoolHubWaitlistSignup)
    -   [signup for school up](using/REST_Actions.md#schoolHubSignup)
    -   [verify school hup signup](using/REST_Actions.md#verifySchoolHubSignup)
    -   [get school hub guilds](using/REST_Actions.md#getSchoolHubGuilds)
    -   [get school hub directory/category counts](using/REST_Actions.md#getSchoolHubDirectoryCounts)
    -   [join guild from school hub](using/REST_Actions.md#joinGuildFromSchoolHub)
    -   [search for guilds in school hub](using/REST_Actions.md#searchSchoolHub)
    -   [get guilds that I'm an owner of that either can potentially be added to the hub or are already in the hub](using/REST_Actions.md#getMySchoolHubGuilds)
    -   [set the description and directory ID of a school hub guild I own](using/REST_Actions.md#setSchoolHubGuildDetails)
    -   [get live stages (from stage discovery)](using/REST_Actions.md#getLiveStages)
    -   [get channel data](using/REST_Actions.md#getChannel)
    -   [get guild activities config](using/REST_Actions.md#getGuildActivitiesConfig)
    -   [get slash commands](using/REST_Actions.md#getSlashCommands)
    -   [click on button or select from menu](using/REST_Actions.md#click)
    -   [trigger/send slash command](using/REST_Actions.md#triggerSlashCommand)
    -	[trigger user command](using/REST_Actions.md#triggerUserCommand)
    -	[trigger message command](using/REST_Actions.md#triggerMessageCommand)
    -   [{gateway} fetch guild members](using/Gateway_Actions.md#gatewayfetchmembers)
    -   [{gateway} guild member fetching parameter helper (POC)](using/Gateway_Actions.md#gatewaygetmemberfetchingparams)
    -   [{gateway} check if guild member fetching is finished](using/Gateway_Actions.md#gatewayfinishedmemberfetching)
    -   [{gateway} find first visible guild channel/category](using/Gateway_Actions.md#gatewayfindVisibleChannels)
    -   [{gateway} subscribe to guild events (use if you're not getting events from large guilds)](using/Gateway_Actions.md#gatewaysubscribeToGuildEvents)
    -   [{gateway} query guild members](using/Gateway_Actions.md#gatewayqueryGuildMembers)
    -   [{gateway} check guild members](using/Gateway_Actions.md#gatewaycheckGuildMembers)
    -   [{gateway} check if guild member searching is finished](using/Gateway_Actions.md#gatewayfinishedGuildSearch)
    -   [{gateway} lazy guild request (opcode 14)](using/Gateway_Actions.md#gatewayrequestlazyguild)
    -   [{gateway} guild member search request (opcode 8)](using/Gateway_Actions.md#gatewayrequestsearchguildmembers)
    -   [{gateway} search slash commands (opcode 24)](using/Gateway_Actions.md#gatewaysearchGuildMembers)
    -   [{gateway} parse GUILD\_MEMBER\_LIST\_UPDATE](using/Gateway_Actions.md#gatewayparseguild_member_list_update)
    -   [{gateway} parse GUILD\_CREATE](using/Gateway_Actions.md#gatewayparseguild_create)
    -   [{gateway} parse GUILD\_MEMBERS\_CHUNK](using/Gateway_Actions.md#gatewayparseguild_members_chunk)
-   Dms
    -   [{risky action} privately message user(s) (create DM / DM Group)](using/REST_Actions.md#createdm)
    -   [remove user from DM group](using/REST_Actions.md#removeFromDmGroup)
    -   [add user to DM group](using/REST_Actions.md#addToDmGroup)
    -   [create DM group invite](using/REST_Actions.md#createDmGroupInvite)
    -   [set DM group name](using/REST_Actions.md#setDmGroupName)
    -   [set DM group icon](using/REST_Actions.md#setDmGroupIcon)
    -   [{gateway} view DM channel request (opcode 13)](using/Gateway_Actions.md#gatewayrequestdmchannel)
-   [Channels](using/Gateway_Actions.md#channels)
    -   [delete channel](using/REST_Actions.md#deleteChannel)
    -   [delete invite](using/REST_Actions.md#deleteInvite)
    -   [get channel invites](using/REST_Actions.md#getChannelInvites)
    -   [{gateway} parse CHANNEL\_CREATE](using/Gateway_Actions.md#gatewayparsechannel_create)
    -   [{gateway} parse CHANNEL\_DELETE](using/Gateway_Actions.md#gatewayparsechannel_delete)
-   Messages
    -   [retrieve past messages](using/REST_Actions.md#getmessages)
    -   [retrieve msg using msg ID](using/REST_Actions.md#getmessage)
    -   [greet someone in a DM](using/REST_Actions.md#greet)
    -   [send embed](using/REST_Actions.md#embedder)
    -   [send message](using/REST_Actions.md#sendmessage)
    -   [send file](using/REST_Actions.md#sendfile)
    -   [reply to message](using/REST_Actions.md#reply)
    -   [search past messages](using/REST_Actions.md#searchmessages)
    -   [parse/filter search results](using/REST_Actions.md#filtersearchresults)
    -   [typing...](using/REST_Actions.md#typingaction)
    -   [edit message](using/REST_Actions.md#editmessage)
    -   [delete message](using/REST_Actions.md#deletemessage)
    -   [pin message](using/REST_Actions.md#pinmessage)
    -   [unpin message](using/REST_Actions.md#unpinmessage)
    -   [get pinned messages](using/REST_Actions.md#getpins)
    -   [add reaction](using/REST_Actions.md#addreaction)
    -   [remove reaction](using/REST_Actions.md#removereaction)
    -   [mark message as read (acknowledge)](using/REST_Actions.md#ackmessage)
    -   [mark message as unread](using/REST_Actions.md#unackmessage)
    -   [mark multiple messages as read (bulk acknowledge)](using/REST_Actions.md#bulkack)
    -   [get trending gifs](using/REST_Actions.md#gettrendinggifs)
    -   [{gateway} parse MESSAGE\_CREATE](using/Gateway_Actions.md#gatewayparsemessage_create)
-   [Stickers](using/REST_Actions.md#stickers)
    -   [get stickers](using/REST_Actions.md#getstickers)
    -   [get sticker apng file](using/REST_Actions.md#getstickerfile)
    -   [get sticker json data](using/REST_Actions.md#getstickerjson)
    -   [get sticker pack data](using/REST_Actions.md#getstickerpack)
-   [Media/Calling](using/Gateway_Actions.md#mediacalling)
    -   [{gateway} start call](using/Gateway_Actions.md#gatewayrequestcall)
    -   [{gateway} end call](using/Gateway_Actions.md#gatewayrequestendcall)
