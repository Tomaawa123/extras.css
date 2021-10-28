/* Don't make a pull request targeting this file. */

/* make links to my carrd use my style */
[href="https://plusinsta.xyz"],
[href="https://plusinsta.xyz/"],
[href="https://PlusInsta.xyz"],
[href="https://PlusInsta.xyz/"] {
	color: #802060 !important;
	border-bottom: 1px solid;
	font-family: Righteous;
}


/* put a nice logo in my server's channel list */
[data-list-item-id="channels___554914403011526675"] .name-3l27Hl {
	font-size: 0;
	background: no-repeat url(//plusinsta.xyz/discord-plus/assets/wordmark_white.svg);
	background-size: 54px 13px;
	width: 54px; height: 13px;
	opacity: 0.6;
}
.theme-light [data-list-item-id="channels___554914403011526675"] .name-3l27Hl {
	background: no-repeat url(//plusinsta.xyz/discord-plus/assets/wordmark_black.svg);
	background-size: 54px 13px;
	width: 54px; height: 13px;
	opacity: 0.7;
}

[data-list-item-id="channels___554914403011526675"]:hover .name-3l27Hl { opacity: 0.7 }
.theme-light [data-list-item-id="channels___554914403011526675"]:hover .name-3l27Hl { opacity: 0.8 }

/* PLEASE READ THE FAQ */
[data-list-item-id="channels___804000972568526889"] .channelName-2YrOjO {
	width: min-content;
	border-radius: var(--dplus-radius-ui);
	border: 3px solid red;
	padding: 3px;
}
[data-list-item-id="channels___804000972568526889"] .channelName-2YrOjO::after {
	content: " <- READ FIRST";
	color: red;
}
/* Make bold text in changelog channels use header font */
[aria-label="changelog (channel)"] strong {
    font-family: var(--dplus-font-header);
}

/* Custom Profiles+ */
	/* Setup */
.banner-2QYc2d, .profileBanner-33-uE1, .headerTop-3vNv-a { background-size: cover; background-repeat: no-repeat; }
.topSection-y3p-_D { background-size: 600px 240px; background-position: bottom; }
.banner-2QYc2d:not(.settingsBanner-15-pZk) { height: var(--dplus-banner-height, 60px); }
.profileBanner-33-uE1 { height: var(--dplus-profilebanner-height, 120px) !important;}
.headerNormal-3KXFBt .bannerPremium-2hSAwz { --dplus-banner-height: 120px; }
.topSection-y3p-_D .bannerPremium-2hSAwz { --dplus-banner-height: 240px; }
.avatarPositionNormal-aZjAsn { top: var(--dplus-avatarpositionnormal, 16px); }
.headerTop-3vNv-a, .topSection-y3p-_D { background-image: var(--dplus-profile-background); }
.nameTag-m8r81H, .nickname-3M3Jfa, .customStatus-1COQYu, .profileBadge-2niAfJ { filter: var(--dplus-dropshadow); }
.headerTop-3vNv-a { background-color: var(--dplus-profilebg-header, var(--dplus-bgc-ui-card)); }
.theme-dark .headerTop-3vNv-a {
	--header-primary: #fff;
	--interactive-active: #fff;
	--text-normal: #dcddde;
	--header-secondary: #b9bbbe;
	--interactive-normal: #b9bbbe;
}

	/* Users with banner images */
[data-user-id="309931975102300160"] /* me! */ {
	--dplus-banner-height: 120px;
	--dplus-profilebanner-height: 240px;
 	--dplus-avatarpositionnormal: 76px; }
[data-user-id="309931975102300160"] .banner-2QYc2d {
	background-image: var(--dplus-background-image) !important;
}
		/* Banner images */
[data-user-id="309931975102300160"] { --dplus-background-image: url('https://fotos-proco.s3.eu-west-3.amazonaws.com/wp-content/uploads/2021/07/17151834/fondos-de-pantallas-para-pc.gif'); }
[data-user-id="367617500021784587"] { --dplus-background-image: url('https://cdn.discordapp.com/attachments/854649169063182336/856214853081497640/IMP.gif'); }

	/* Users with profile backgrounds */
[data-user-id="309931975102300160"],
[data-user-id="275432265100558336"],
[data-user-id="220275692926009344"],
[data-user-id="367617500021784587"],
[data-user-id="394891840815366147"],
[data-user-id="644964603108786233"],
[data-user-id="356817504330448906"] {
	--dplus-dropshadow: drop-shadow(0px 0px 2px black);
	--dplus-profilebg-header: transparent; }
 		/* Profile backgrounds */
[data-user-id="309931975102300160"] { --dplus-profile-background: url(https://cdn.discordapp.com/attachments/854649169063182336/856197355190616084/output.webp); }
[data-user-id="275432265100558336"] { --dplus-profile-background: url(https://cdn.discordapp.com/attachments/854649169063182336/856197380230742036/output.webp); }
[data-user-id="220275692926009344"] { --dplus-profile-background: linear-gradient(#FD008380,#FD008380); }
[data-user-id="367617500021784587"] { --dplus-profile-background: linear-gradient(#00FFFF80,#00FFFF80); }
[data-user-id="394891840815366147"] { --dplus-profile-background: linear-gradient(#ffcbec80,#ffcbec80); }
[data-user-id="644964603108786233"] { --dplus-profile-background: url(https://cdn.discordapp.com/attachments/854649169063182336/856189355874189312/output.webp); }
[data-user-id="356817504330448906"] { --dplus-profile-background: url(https://i.pinimg.com/originals/37/51/93/37519305e9a09c3703f6305fb6e5b43c.gif); }

/* Supporters */
[data-user-id="220275692926009344"],
[data-user-id="367617500021784587"],
[data-user-id="719378258491342878"],
[data-user-id="644964603108786233"],
[data-user-id="299958646748741632"],
[data-user-id="354342865695932423"],
[data-user-id="275432265100558336"],
[data-user-id="852664018438717481"],
[data-user-id="299339580593799171"],
[data-user-id="224367608382619648"],
[data-user-id="356817504330448906"] {
	--dplus-badge: url("//plusinsta.xyz/discord-plus/assets/badges/badge_supporter.svg");
	--dplus-supporter: "";
}
/* Developers */
[data-user-id="309931975102300160"],
[data-user-id="207335168430702602"],
[data-user-id="394891840815366147"] {
	--dplus-badge: url("//plusinsta.xyz/discord-plus/assets/badges/badge_dev.svg");
	--dplus-dev: "";
}

/* Badges */
.headerText-15Q25Z:after, .headerTop-547GTz:before,
.headerTag-16AlQV:after, .topSection-y3p-_D header:after
	{ filter: drop-shadow(0px 0px 2px black); }
.headerText-15Q25Z:after, .headerTop-547GTz:before
{ background-image: var(--dplus-badge);
	width: 120px; height: 25px; background-repeat: no-repeat; content: var(--dplus-dev, var(--dplus-supporter)); display: block; z-index: 0; }

	/* D+ badge in member list */
.name-uJV0GL:after {
	content: var(--dplus-dev, var(--dplus-supporter));
	background-image: var(--dplus-badge-memberlist);
	margin-left: 3px;
	display: inline-block;
	width: 14px; height: 14px;
}

.theme-dark { --dplus-badge-memberlist: url("//cdn.discordapp.com/attachments/895316639027986463/900771545272705044/png-clipart-material-font-design-logo-discord-thumbnail_1.png"); }
.theme-light { --dplus-badge-memberlist: url("https://cdn.discordapp.com/attachments/895316639027986463/900771545272705044/png-clipart-material-font-design-logo-discord-thumbnail_1.png"); }

	/* Badge for Michelle */
[data-user-id="220275692926009344"] .headerTag-16AlQV:after,
[data-user-id="220275692926009344"] .topSection-y3p-_D header:after
{ background-image: url("//plusinsta.xyz/discord-plus/assets/badges/badge_vip_michelle.svg");
	width: 96px; height: 20px; background-size: cover; content: ""; display: block; z-index: 0; }
[data-user-id="220275692926009344"] .topSection-y3p-_D header:after
{ margin-left: 16px; }
[data-user-id="220275692926009344"] .nameTag-ECvD8P
{ margin-bottom: 0; }

/* Make my own profile Different(TM) */
[data-user-id="309931975102300160"] .nickname-3M3Jfa,
[data-user-id="309931975102300160"] .username-2b1r56 {
	font-size: 28px;
}
[data-user-id="309931975102300160"] .discriminator-1swucG {
	opacity: 0;
}
[data-user-id="309931975102300160"] .username-2b1r56:after {
	font-size: 16px;
	content: "#0001";
	color: var(--header-secondary);
}
[data-user-id="309931975102300160"] .nickname-3M3Jfa:after {
	font-size: 16px;
	content: " (Insta#0001)";
	color: var(--header-secondary);
}
[data-user-id="309931975102300160"] .discrimBase-24vY8o,
[data-user-id="309931975102300160"] .headerTagWithNickname-3l_x6x .headerTagUsernameBase-1NqrY5 {
	display: none;
}
