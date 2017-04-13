/*
  DarkMonoAlt - Tweaked by mnster for PassTheHeadphones
  -----------------------------------------------------

  Original DarkMono v2 by htrd (a.hatred@gmail.com)
  Original terms of use / license information:

  Everything is copyright 2012 htrd.
  Distributed under the Creative Commons BY-NC-ND 3.0 License:
    * You may copy, distribute and transmit this stylesheet and it's associated elements, unaltered and in their entirety, so long as you
      give proper credit for the creation and design of these elements to htrd and include this written notice of such credit.
    * You may not use any aspect of this stylesheet or it's design elements for any commercial or public purposes.
    * You may not alter, transform, or build upon this stylesheet for public use.
    * By using this stylesheet and it's associated elements, you agree to these Terms of Use and also that these Terms of Use may change at any time, with or without notice.
  Made exclusively for use on What.CD in 2012.
*/
@import url("https://fonts.googleapis.com/css?family=Roboto:400,700");
* {
  margin: 0;
  padding: 0;
}

body {
  margin: 0;
  padding: 0;
  background: #222;
  color: #9A9A9A;
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.3);
  font: 13px 'Roboto', 'Trebuchet MS', "Arial", sans-serif;
}

p, #userinfo_stats li:last-child {
  margin: 0;
}

p.min_padding, .friends_table td.left input[type="submit"]:first-child {
  margin-top: 3px;
}

table {
  border-spacing: 0;
  border-collapse: collapse;
}

ol, ul {
  list-style-position: inside;
}

li {
  line-height: 1.5em;
}

a, .linkbox a:hover {
  color: #528ba3;
  text-decoration: none;
}

a:hover, #content a:visited {
  color: #456478;
}

a img, #collage .search_form td, #requests .search_form td, #reportsv2 #reportform.create_form .layout td, #requests .box.box_votes td, #upload #whmf_offer, .filter_torrents .cat_list, .search_form .layout td {
  border: none !important;
}

.add_bookmark a, .big_info .add_bookmark.brackets, .bookmark a.add_bookmark {
  display: block;
  overflow: hidden;
  padding: 2px 0px;
  width: 20px;
  height: 20px;
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/bm-add.png") no-repeat top left;
  background-position: 0px 5px;
  text-indent: 100%;
  white-space: nowrap;
  font-size: 0px;
  cursor: pointer;
}

.remove_bookmark a, .big_info .remove_bookmark.brackets, .bookmark a.remove_bookmark {
  display: block;
  overflow: hidden;
  padding: 2px 0px;
  width: 20px;
  height: 20px;
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/bm-remove.png") no-repeat top left;
  background-position: 0px 5px;
  text-indent: 100%;
  white-space: nowrap;
  font-size: 0px;
  cursor: pointer;
}

/*
a.upvote, a.small_upvote {
    display: inline-block;
    overflow: hidden;
    width: 16px;
    height: 14px;
    background: url('https://redacted.ch/static/styles/dark_mono_v2/img/notifications.png') no-repeat top left;
    background-position: 0px -62px;
    text-indent: 100%;
    white-space: nowrap;
    cursor: pointer;
}

a.upvote:hover, a.small_upvote:hover {
    display: inline-block;
    overflow: hidden;
    width: 16px;
    height: 14px;
    background: url('https://redacted.ch/static/styles/dark_mono_v2/img/notifications.png') no-repeat top left;
    background-position: -16px -62px;
}

a.downvote, a.small_downvote {
    display: inline-block;
    overflow: hidden;
    width: 16px;
    height: 14px;
    background: url('https://redacted.ch/static/styles/dark_mono_v2/img/notifications.png') no-repeat top left;
    background-position: 0px -76px;
    text-indent: 100%;
    white-space: nowrap;
    cursor: pointer;
}

a.downvote:hover, a.small_downvote:hover {
    display: inline-block;
    overflow: hidden;
    width: 16px;
    height: 14px;
    background: url('https://redacted.ch/static/styles/dark_mono_v2/img/notifications.png') no-repeat top left;
    background-position: -16px -76px;
}

a.small_clearvote {
    display: inline-block;
    overflow: hidden;
    width: 16px;
    height: 14px;
    background: url('https://redacted.ch/static/styles/dark_mono_v2/img/notifications.png') no-repeat top left;
    background-position: 0px -91px;
    text-indent: 100%;
    white-space: nowrap;
    cursor: pointer;
}
*/
a.new-subscriptions {
  padding: 6px 5px 5px !important;
  margin-right: 5px;
  background-color: rgba(42, 68, 93, 0.1);
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(42, 68, 93, 0.1)), to(rgba(76, 123, 167, 0.5)));
  background-image: -webkit-linear-gradient(top, rgba(42, 68, 93, 0.1), rgba(76, 123, 167, 0.5));
  background-image: -moz-linear-gradient(top, rgba(42, 68, 93, 0.1), rgba(76, 123, 167, 0.5));
  background-image: -o-linear-gradient(top, rgba(42, 68, 93, 0.1), rgba(76, 123, 167, 0.5));
  background-image: linear-gradient(to bottom, rgba(42, 68, 93, 0.1), rgba(76, 123, 167, 0.5));
  color: #888;
}

a.new-subscriptions:hover {
  color: #7a7a7a !important;
}

a.hide_torrents_link {
  display: block;
  width: 23px;
  height: 25px;
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/show-hide.png") no-repeat;
  background-position: 0px -25px;
}

a.show_torrents_link {
  display: block;
  width: 23px;
  height: 25px;
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/show-hide.png") no-repeat;
}

h1, h2, h3 {
  color: #666 !important;
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.2);
  font-weight: bold;
}

h2 {
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.2);
  font-size: 24px;
  line-height: 1.2em;
  margin-bottom: 1em;
}

h3 {
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.2);
  font-size: 14px;
  line-height: 1.2em;
  margin-bottom: 1.1em;
}

h4, h5, .thin > h2 + .linkbox + div table td:first-child, .filter_torrents table:nth-child(1) td:first-child, .add_torrent_container .add_form span[style="font-style: italic;"] {
  font-size: 12px;
}

h3#irc + .box.pad ul li:last-child, h3#general + .box.pad ul li:last-child {
  margin-bottom: 0;
  padding-bottom: 0;
  border-bottom: none;
}

#alerts {
  position: absolute;
  top: 90px;
  text-align: right;
}

#artist .merge_form div[style="text-align: center;"] {
  text-align: left !important;
}

#artist .merge_form div[style="text-align: center;"] label:first-child {
  margin-left: 50px;
}

#artist .merge_form div[style="text-align: center;"] label {
  margin-left: 29px;
}

#artist .merge_form div[style="text-align: center;"] strong {
  margin-left: 72px;
}

#artist .merge_form div[style="text-align: center;"] input[type="submit"] {
  margin-left: 444px;
}

#artist .add_form input[value="Add alias"] {
  margin-top: 10px;
  margin-left: 463px;
}

#artist .merge_form input#newartistid, #artist .merge_form input#newartistname {
  width: 87%;
}

#artistcomplete, #torrentscomplete {
  position: absolute !important;
  z-index: 2;
  display: block !important;
  overflow: hidden;
  width: 152px !important;
  background: rgba(20, 20, 20, 0.8);
  text-align: left;
}

#artistcomplete > li {
  display: block;
  padding: 5px 5px !important;
  width: 100% !important;
  cursor: pointer;
}

#artistcomplete li.highlight {
  margin-right: 0;
  background-color: rgba(100, 100, 100, 0.55);
}

#artistfields input#artist, #title_tr input#title, #label_tr input#record_label, #catalogue_tr input#catalogue_number, #upload_table.create_form input#image, #edition_title input#remaster_title, #edition_record_label input#remaster_record_label, #edition_catalogue_number input#remaster_catalogue_number, .yadg_tr input#yadg_input, #upload_table.create_form input#title {
  width: 350px;
}

#artist_list .remove.remove_artist, #info.head a:last-child, #concerts.head a:last-child, .box.box_info.pad ul ul li a:nth-child(2), .box.box_info.pad ul ul li a:nth-child(3), a#flip_to, #torrents .submit input[value="Filter Torrents"], .group_torrent td span, .votespan {
  float: right;
}

#artist_name.ftr_advanced td, #search_terms.ftr_basic td {
  padding-top: 0;
}

#better .search_form input[size="60"] {
  width: 500px;
}

#better .search_form tr:hover, #wrapper div::-webkit-scrollbar-corner {
  background-color: transparent;
}

#better .torrent_table .torrent_info, #better .torrent_table .tags {
  margin-left: 30px;
}

#bookmarks .torrent_table .colhead_dark td:first-child {
  width: 5%;
}

#bookmarks .search_form .layout.border, #bookmarks .search_form .layout.cat_list {
  margin: 0;
  -webkit-box-shadow: none;
  box-shadow: none;
}

#collage table#discog_table tr.group_torrent td:first-child, #bookmarks table#torrent_table tr.group_torrent td:first-child, #torrents table#torrent_table tr.group_torrent td:first-child, #top10 tr.group_torrent td:first-child {
  padding-left: 76px;
}

#collage_table {
  margin-bottom: 20px;
  border: none;
  background: none;
  -webkit-box-shadow: none;
  box-shadow: none;
}

#collage_table td img {
  margin: 2px;
  width: 128px;
  height: 128px;
  border: 2px solid #3b3b3b;
  opacity: 0.6;
}

#collage_table td img:hover {
  border: 2px solid #5fa296;
  opacity: 1;
  transition: opacity .25s ease-in-out;
  -webkit-transition: opacity .25s ease-in-out;
  -moz-transition: opacity .25s ease-in-out;
  -o-transition: opacity .25s ease-in-out;
}

#collage .search_form .layout.border tr:nth-child(3) td:nth-child(2) label, tr#release_list td label, tr#format_list td label, tr#bitrate_list td label, tr#media_list td label {
  margin-right: 10px;
}

#collage form#quickpostform.send_form textarea[cols="24"], .sidebar .add_form textarea {
  margin-bottom: 5px;
  width: 216px !important;
}

#collage .create_form .layout td.center, #upload .layout.border.slice tbody tr td table td, .forum_post td, .search_form .layout td, .friends_table td, #torrents .edit_form .layout.border td, #wiki .layout.border td, #better .search_form td, #edition_information td, #user .send_form .layout.border td {
  border: none;
}

#collage input#namebox, #collage input#tags, #newthreadtext input#title, input#pollquestionfield, #newthreadtext textarea#posttext, #user form textarea[style="width: 100%"], #user form input[style="width: 100%"], #requests #request_form textarea[name="description"] {
  width: 757px !important;
}

#collage select[name="category"] {
  margin-bottom: 3px;
}

#collage .search_form .layout.border tr:nth-child(4) td:nth-child(3) {
  width: 60px;
}

#content h1 a:visited, #content h2 a:visited, #content h3 a:visited {
  color: #528ba3 !important;
}

#catalogue_number_year td:nth-child(3), #edition_title td:nth-child(3) {
  width: 175px;
}

#content {
  overflow: hidden;
  margin: 150px auto 50px !important;
  width: 1000px;
  line-height: 1.4em;
}

#content .main_column {
  float: left;
  width: 730px;
}

#content, .thin {
  clear: both;
  overflow: hidden;
}

#content .sidebar {
  float: right;
  width: 258px !important;
}

#coverart.box ul.collage_images img {
  margin: 5px;
  width: 130px !important;
  height: 130px !important;
  border: 2px solid #3b3b3b !important;
  opacity: 0.8;
}

#coverart.box ul.collage_images img:hover, .group_image.float_left.clear img:hover, .gm_albumartdisplay img:hover, #collage_table td img:hover, #userhistory .torrent_table.grouped.artwork tr.group.discog td[style="width: 60px; padding: 0;"] img:hover, #user .layout.recent a > img:hover {
  border: 2px solid #528BA3 !important;
  opacity: 1 !important;
  transition: opacity .25s ease-in-out;
  -webkit-transition: opacity .25s ease-in-out;
  -moz-transition: opacity .25s ease-in-out;
  -o-transition: opacity .25s ease-in-out;
}

#debug_database pre, #debug_report pre {
  white-space: pre-wrap;
}

#debug_sphinx .debug_sphinx_time, #debug_database .debug_query_time, #debug_flags .debug_flags_time {
  width: 200px;
}

#desc_row textarea {
  width: 618px;
  float: right;
  margin-left: 10px !important;
}

#desc_row a {
  clear: both;
  line-height: 30px;
}

#discog_table .box.center {
  color: #444 !important;
}

#discog_table .box.center a {
  padding: 2px;
}

#donate img[alt="Flattr this"] {
  margin: 8px 0 5px 10px;
}

#donate input[type="submit"] {
  margin: 10px 5px 0 0;
}

#dnulist td:first-child {
  width: 30% !important;
}

#dnulist td:last-child {
  width: 70% !important;
}

#extra1 {
  position: absolute;
  top: 0;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 45px;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  background: #191919;
}

#extra2 {
  position: absolute;
  top: 0;
  margin: 125px 0 0;
  width: 100%;
  height: 50px;
  background-color: #2e2e2e;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
}

#flip_view_1, #flip_view_2, canvas#similarArtistsCanvas {
  margin: auto;
}

#footer {
  margin: 0 auto 50px;
  width: 1000px;
  text-align: center;
}

#footer:after {
  content: "DarkMonoAlt by mnster. Original by htrd. Released under CC BY-NC-ND 3.0 License.";
}

#greasemonkey_status_area {
  top: 50px !important;
}

#header {
  position: relative;
  z-index: 5;
  margin: 0 auto;
  width: auto;
  max-width: 1300px;
  height: 65px;
}

#format-hide, .torrent_table, #content > .search_form, .thin > div > .search_form, .box.pad .edit_form, .box.pad .rename_form, .box.pad .merge_form, .vote_matches_table, .main_column > .box, .sidebar .box, .collage_table, .create_form .layout, .request_table .border, .request_table.border, #request_form .layout, #searchforum, .forum_index, .forum_post, .forum_list.border, #reply_box, #chat .box.pad[style="padding: 10px 10px 10px 20px;"], #top10 h3 + .border, .rule_summary, .rule_table, .box.pad > .border, .thin > .before_rules, #actual_rules, .thin > .search_form, #wiki .create_form, #wiki .edit_form, #wiki .thin > form > table, #below_box, .staff, #logchecker .thin > form > table, #better .box.pad[style="padding: 10px 10px 10px 20px;"] > p, #better .box.pad > table[width="100%"], .message_table, #inbox .send_form, .edit_form .layout, .friends_table, #dnulist, #upload .thin > p, #upload .box.pad > h3 + p + p, #user .box.pad > table[width="100%"], #donate .box.pad, #user .thin > .header + .box.pad, #user .send_form .layout.border, #discog_table .box.center, #user .main_column .layout.recent, #user .manage_form .layout, .artist_table, #manage_collage_table.ui-sortable, .thin > .header + .layout, #wiki .thin > .header + table, .main_column > .layout, .box.vertical_space, .manage_form .box.pad, .split_form .layout, .box.pad .add_form, .thin > .header + .border, #searchthread .search_form .layout.border, #content > .header + .linkbox + .layout.border, .thin > .box.thin.clear, #compose .send_form, #torrents .thin.center > .box[style="width: 600px; margin: 0px auto;"], #blog .box, #wiki .thin > div > form > .layout.border, #forums #searchthread.center .search_form .layout.border, #wiki .thin > .linkbox + table[width="100%"], #reports .thin > h3 + .box.pad, #reports .thin > .box.pad + p + table, #torrents .thin > .header + table, #staffpm #inbox > .box.pad, #torrents .torrentdetails.pad table, #user #content > .thin.center > .box, #log #log_table.log_table.border, #mark_suggestion_div .layout.border, #tools #content table, #recommendation_div {
  margin-bottom: 15px !important;
  padding: 10px !important;
  background-color: rgba(100, 100, 100, 0.15);
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  color: #9A9A9A;
}

#forums .colhead_dark strong > a {
  text-transform: none;
}

#forums #searchforum .search_form {
  width: 970px;
  color: #9A9A9A;
}

#forums #searchforum.center {
  margin-top: 10px;
  text-align: justify;
}

#forums #content blockquote {
  margin-bottom: 5px;
  max-width: 805px;
}

#forums #quickreplytext br, #torrents .edit_form br, #rules li[id="r2.2.0"] img, #rules li[id="r2.2.0"] em, .sidebar .box.box_addtag br, #collage form#quickpostform.send_form br, #quickreplytext br, .add_torrent_container .add_form br, .user_title br, .main_column div#coverart + br, #upload .thin > p br, #upload #content > .box.pad + br, #rules .thin > .box.pad + br, #rules .header + br, #rules form + br, .main_column .linkbox + br, #quickpost h3 + input + br, #threadpoll.pad br, #staffpm .thin > br, #staff .box.pad br, #staff .thin > br, #blog div + br, #staffpm #messageform.manage_form br, #bookmarks .group.discog td > span > br, .sticky_post_label, .send_form > .box.pad > br, #recommendation_status br {
  display: none;
}

#forums pre {
  max-width: 700px;
}

#forums .linkbox strong + br + a {
  line-height: 18px;
}

#forums .search_form .cat_list td {
  text-align: left;
}

#forums .search_form .cat_list .forum_cat {
  text-align: center;
}

#format-hide span {
  padding: 2px 2px;
  border: none !important;
  color: #528ba3 !important;
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.3);
}

#format-hide .hider-f {
  padding: 2px 2px;
  color: #666 !important;
  text-decoration: none !important;
}

#format-hide.box.box_artists {
  color: rgba(100, 100, 100, 0.15);
  text-shadow: none;
}

#friends .friends_table textarea {
  height: 73px;
}

#friends .friends_table td.left input[type="submit"] {
  margin-bottom: 5px;
  width: 100%;
}

#friends .friends_table tr.colhead span[style="float: right;"]:before {
  content: "Last Seen: ";
}

#index .sidebar .box .pad p, .linkbox .center, #artist .thin > h2, #index .sidebar .box div.head.colhead_dark + div.center.pad, .rule_summary li, #quickreplytext, #staff .box.pad h3 + p, #reports .box.pad + p, #reports .box.pad > p, #rules h4, #rules h5, .edit_form div > h3 + p, .send_form .box.pad textarea#quickpost, #reports blockquote, .save_message {
  margin-bottom: 5px;
}

#index .graph .center_poll {
  margin-top: 0;
}

#index .sidebar a > img[width="100%"], .box.box_albumart img, #artist .sidebar div img {
  width: 230px;
  height: auto;
  border: 2px solid #3b3b3b !important;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  opacity: 1;
}

#index .sidebar a > img[width="100%"]:hover, #artist .sidebar div img:hover, .box.box_albumart img:hover {
  border: 2px solid #456478 !important;
  opacity: 0.6;
  -webkit-transition: opacity .25s ease-in-out;
  -moz-transition: opacity .25s ease-in-out;
  transition: opacity .25s ease-in-out;
}

#inbox #quickpost input[type="text"], #staffpm .send_form input#subject, #staff .send_form input#subject, #artist .edit_form input[size="92"], #artist .rename_form input[name="name"], #artist .add_form input[size="40"], #torrents .rename_form input[size="92"], #torrents .merge_form input[name="targetgroupid"], .box.pad .edit_form input[size="92"] {
  display: block;
  margin: 0 auto 10px;
  width: 958px;
}

#inbox .box.pad input[value="Editor"], #inbox .box.pad input[value="Preview"] {
  margin-right: 3px;
}

#inbox .manage_form .layout td {
  padding-top: 10px;
  border: none;
}

#inbox .manage_form .layout td.label, #requests .box.box_votes td:nth-child(2), .thin > h2 + div > form table td.label, .thin > h2 + .linkbox + div form table td.label, .filter_torrents td.label, #requests tbody tr td.label, #requests .thin .search_form tr#release_list td.label, #collage .thin .search_form tr td.label, #logchecker .thin.center .border td.label, #upload #upload_table.create_form #dynamic_form table tbody td:first-child, #userform.edit_form .layout td.label {
  text-align: right;
}

#inbox .thin #searchbox.search_form div input:last-child, #index .sidebar #merchbox.box div.center.pad, #index .sidebar .box div.center.pad:last-child, #reports .box.pad ul + p, #inbox input[value="Manage conversation"], #artistfields input[id="artist"]:nth-child(n+1), .artists_with, .preview_submit, #answer_block input:nth-child(n+2) {
  margin-top: 5px;
}

#lightbox {
  position: fixed;
  top: 10%;
  left: 5%;
  z-index: 1000;
  overflow: auto;
  padding: 0;
  width: 90%;
  height: 90%;
  text-align: center;
}

#lightbox img {
  max-width: 90%;
  max-height: 90%;
  border: 5px solid #3b3b3b;
}

#logchecker textarea#log_contents {
  margin: 0 !important;
  height: 100px;
  width: 757px;
}

#logchecker blockquote h2 {
  margin-bottom: 0px;
}

#logo a {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 5;
  margin: 8px 0 0 50px;
  padding: 0;
  width: 113px;
  height: 30px;
  background-image: url('https://ptpimg.me/8m83pi.png');
  background-repeat: no-repeat;
  background-size: auto 100%;
  background-position: center center;
}

#menu {
  position: absolute;
  top: 0;
  right: 0;
  width: 100%;
  height: 45px;
  text-align: right;
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.5);
  font-weight: normal;
}

#menu a, #userinfo_stats a, .tags a:hover, .search_form {
  color: #9A9A9A;
}

#menu .active a {
  background-color: #1c1c1c;
  color: #F9A440;
}

#menu .active a:hover {
  color: #aaa;
}

#menu ul {
  padding: 15px 0 0 50px;
}

#menu ul li:last-child {
  margin-right: 55px;
}

#menu li:first-child, #inbox .manage_form .layout td.center, .search_form .layout tr:last-child td.center, .debug_table td.debug_data, .drag_drop_save {
  padding: 0;
}

#menu li a, #menu li a:hover {
  padding: 13px 7px 15px;
}

#nav_userinfo, #nav_useredit, #nav_logout, #nav_upload, #nav_invite, #nav_donate, #nav_store {
  display: inline-block !important;
  height: 15px;
}

/*
#nav_useredit, #nav_logout, #nav_invite, #nav_donate, #nav_store {
    opacity: 0;
    transition: opacity .25s ease-in-out;
    -webkit-transition: opacity .25s ease-in-out;
    -moz-transition: opacity .25s ease-in-out;
    -o-transition: opacity .25s ease-in-out;
}

#userinfo_username:hover #nav_useredit, #userinfo_username:hover #nav_logout, #userinfo_major:hover #nav_invite, #userinfo_major:hover #nav_donate, #userinfo_major:hover #nav_store {
    opacity: 1;
}
*/
#other_bitrate_span input#vbr {
  top: 3px;
}

#quickreplytext .bbcodes, #messageform .bbcodes, .edit_form .bbcodes, .friends_table .bbcodes, #newthreadtext .bbcodes, .create_form .bbcodes, .send_form .bbcodes, .forum_post form .bbcodes, #requests #request_form .bbcodes {
  max-width: 100% !important;
}

#recommended .head {
  margin-bottom: -11px !important;
}

#recommendation_note {
  width: 600px;
}

#requests #request_form.add_form, #requests .edit_form {
  margin: 0 !important;
  padding: 0 !important;
  background: none !important;
}

#requests #request_form select#importance {
  margin: 0 2px;
  width: 112px;
}

#requests #request_form input#tags {
  margin-left: 2px;
  width: 265px;
}

#requests .layout form[name="request"] {
  -webkit-box-shadow: none !important;
  box-shadow: none !important;
}

#requests .thin div:nth-child(3) form table:nth-child(6) td {
  padding: 13px 0 0 0 !important;
  padding-top: 13px !important;
  border-bottom: 0 !important;
}

#requests .main_column .layout td > .edit_form input[size="50"] {
  width: 50%;
}

#requests .forum_post form textarea[cols="80"], #torrents .main_column .forum_post.box.vertical_margin form textarea[cols="50"] {
  width: 538px;
}

#reportform .box.pad input, #reportform textarea {
  max-width: 705px;
  width: 705px;
}

#reportform td.label {
  width: 220px;
}

#rules .search_form input#search_string, #debug_loggedvars .debug_loggedvars_name {
  width: 290px;
}

#rules li[id="r2.2.0"] p {
  margin-bottom: 10px;
  margin-left: 14%;
  width: 675px;
  height: 275px;
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/trump.png") no-repeat !important;
}

#rules span#Index {
  margin-left: 5px;
  font-size: 90%;
}

#rules .ratio_table {
  margin: 10px 0;
  margin-left: 250px;
  width: 500px;
  background: rgba(50, 50, 50, 0.4);
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
}

#rules .rule_summary > ul, #chat .thin .box.pad > ul {
  padding: 10px 20px 10px 30px;
  list-style-type: lower-roman;
}

#rules .box.pad.rule_summary > p {
  text-align: justify;
}

#rules ol, #rules ul, #wiki .box_info.pad ul, #chat .box.pad ul {
  list-style: none;
}

#searchbars {
  position: absolute;
  top: 125px;
  margin: 0;
  padding: 12px 5px;
  width: 100%;
  height: 28px;
  text-align: center;
}

#searchbars ul li {
  display: inline-block;
  margin-right: 5px;
}

#searchbars li:last-child, #userinfo_stats li:last-child {
  margin-right: 0;
}

#searchbars ul, #searchbars form {
  display: inline;
  margin: 0;
  padding: 0;
}

#searchbars input {
  padding: 5px 10px;
  width: 130px;
  height: 15px;
  border: 1px solid #3B3B3B;
  background: rgba(0, 0, 0, 0.15);
  -webkit-box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  color: #666;
  transition: .25s ease-in-out;
  -webkit-transition: .25s ease-in-out;
  -moz-transition: .25s ease-in-out;
  -o-transition: .25s ease-in-out;
}

#site_debug .debug_table .debug_data > div, #site_debug .debug_table .debug_data > pre {
  overflow: auto;
  padding: 8px;
  max-width: none;
  max-height: 400px;
}

#sortable li {
  margin-bottom: 5px;
  font-size: 100% !important;
  padding-left: 1px;
  margin-left: 0;
}

#sortable {
  -webkit-column-width: 110px;
  -moz-column-width: 110px;
  column-width: 110px;
  width: 100% !important;
}

#stats .box.pad.center img {
  margin: 10px 0;
}

#stats .box.center img:last-child, #recommended #vanityhouse {
  margin-top: 20px;
}

#staff .send_form strong, #staffpm .send_form strong {
  margin-left: 33%;
}

#staffpm #compose, .thin > h2 + div, .thin > h2 + .linkbox + div, .sidebar .download_form ul#list.nobullet, .sidebar .box.box_addtag .add_form, .sidebar form[action="bookmarks.php"] ul#list.nobullet, #artist .box.pad > ul, #artist .add_form input[size="40"], #torrents .edit_form div.yadg_div, blockquote.log_bad, #preview, #inbox #messageform.manage_form input[type="submit"], input.save_sortable_collage {
  margin-bottom: 10px;
}

#searchthread .search_form {
  width: 1000px;
}

#threadpoll p {
  margin-bottom: 20px;
  font-size: 16px;
}

#tools #marked_suggestion table, #tools #implemented_suggestion table, #tools #rejected_suggestion table {
  width: 300px;
}

#tools #marked_suggestion {
  float: left;
  margin-right: 50px;
}

#tools #implemented_suggestion {
  float: left;
}

#tools #rejected_suggestion {
  float: right;
}

#top10 .thin div[style="text-align: right;"] {
  margin: 10px 0 15px;
  text-align: center !important;
}

#top10 input[name="year2"], a.downvote, a.small_downvote, .box.box_info.pad a[title="Delete Alias"], #user .delete_form input[value="Logout"], #user .delete_form input[value="Current"], input#remove_format, .send_form .layout.border input[value="Invite"] {
  margin-left: 5px;
}

/*
#top10 span[style="float: right;"], span#vote_message {
    font-size: 0px;
    line-height: 0;
}
*/
#top10 tr.colhead_dark td[width="70%"] {
  width: auto;
}

#top10 tr.colhead_dark td:first-child, #top10 tr.colhead_dark td:nth-child(2), #top10 tr.colhead_dark td.sign {
  width: 20px;
}

#torrent_table tr.group:hover img, #discog_table tr.discog:hover img, .torrent_table.cats.numbering.border tr.torrent:hover img, .torrent_table tr.torrent_row:hover img, .torrent_table tr.torrent:hover img {
  border: 2px solid #528BA3 !important;
  opacity: 1 !important;
  transition: opacity .25s ease-in-out;
  -webkit-transition: opacity .25s ease-in-out;
  -moz-transition: opacity .25s ease-in-out;
  -o-transition: opacity .25s ease-in-out;
}

/* Hover opacity for artwork in torrent lists */
#torrents .submit input[value="Reset"] {
  float: left;
}

#torrents .thin > h2 + div > form .submit, #collage .thin form .submit {
  padding-top: 13px;
}

#requests .thin div:nth-child(3) form table:nth-child(3) tr:first-child td, #collage .thin form table:nth-child(2) tr:first-child td, #req .thin form table:nth-child(2) tr:first-child td {
  padding-top: 0 !important;
}

#torrents .search_form .submit {
  margin-top: 10px;
  text-align: center;
}

#torrents .edit_form select#releasetype {
  margin-bottom: 10px;
  margin-left: 452px;
}

#torrents .edit_form .layout.border td.center, #rules .header > h2.center, .yadg_div h3, #torrents .thin.center > .box .head.colhead {
  text-align: left;
}

#torrents .edit_form .layout.border td.label:after {
  content: ": ";
}

#torrents .edit_form .layout.border, #forums .search_form .layout.border, #vanityhouse.torrent_table {
  background: none;
  -webkit-box-shadow: none;
  box-shadow: none;
}

#torrents .edit_form input[value="Edit"] {
  margin-left: 468px;
  width: 44px;
}

#torrents .edit_form .layout.border td.label {
  width: 100px;
  text-align: right;
}

#torrents .edit_form input[size="40"] {
  width: 838px;
}

#torrents .thin.center > .box .delete_form input[name="extra"] {
  width: 677px;
}

#upload_table.create_form textarea#album_desc, #upload_table.create_form textarea#release_desc, #userform.edit_form textarea#info, #upload_table.create_form textarea#desc {
  max-width: 757px !important;
}

#userform.edit_form .layout td > label {
  line-height: 20px;
}

#userform.edit_form .layout.border .layout, #recommended #vanityhouse {
  margin-bottom: 0;
}

#userinfo a, #menu a, #searchbars a {
  transition: .25s ease-in-out;
  -webkit-transition: .25s ease-in-out;
  -moz-transition: .25s ease-in-out;
  -o-transition: .25s ease-in-out;
}

#userinfo {
  overflow: hidden;
  width: 100%;
}

#userinfo ul {
  position: absolute;
  padding: 0;
}

#userinfo_username {
  position: static !important;
  left: 0;
  float: left !important;
  overflow: hidden;
  margin: 62px 0 0 50px;
  height: 1.5em !important;
  text-align: left;
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.5);
}

#userinfo_username li, #userinfo_stats li, #userinfo_minor li, #userinfo_major li, #searchbars, #menu li {
  display: inline;
  line-height: 14px;
}

#userinfo_username:hover, #userinfo_major:hover, ul.collage_images li a {
  height: auto !important;
}

#userinfo_major {
  position: static !important;
  left: 0;
  z-index: 20;
  float: left !important;
  overflow: hidden;
  margin: 62px 0 0 5px;
  height: 1.5em !important;
  text-align: left;
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.5);
}

#userinfo_stats {
  opacity: 0.8;
  left: 0;
  z-index: 1;
  margin: 90px 0 0 50px;
  text-align: right;
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.5);
  font-size: 12px;
}

#userinfo_stats li, #userinfo_major li, #userinfo_username li, #userinfo_minor li:last-child, #searchbars li, #top10 input[name="year1"], #answer_block input:first-child, #user #content > .thin.center > .box form strong {
  margin-right: 5px;
}

#userinfo_minor {
  right: 0;
  margin: 62px 50px 0 0;
}

#userinfo_minor li, #userinfo_major li {
  padding-right: 5px;
}

#userinfo_major li:last-child, #userinfo_username li:last-child {
  padding-right: 0;
}

#userinfo_minor a, #userinfo_username a, #userinfo_major a, #menu a:hover, #userinfo_stats a:hover {
  padding: 2px 0px;
  color: #666;
}

#userinfo_username a.username {
  color: #528ba3;
  font-weight: normal;
  font-size: 13px;
}

#userinfo_minor a:hover, #userinfo_major a:hover, #userinfo_username a:hover {
  color: #444;
}

#user #content > .thin.center > .box form input[maxlength="100"] {
  width: 600px;
}

#user input[type="url"], #userform.edit_form small {
  margin-left: 242px;
  margin-top: 5px;
}

#user input#avatar, #user input#email, #user input#irckey, #user input[type="password"], #requests #request_form input#yadg_input, #requests #request_form input[size="45"], #artist .merge_form input[size="40"] {
  width: 400px;
}

#user .layout.recent tr:nth-child(n+2) td, .search_form tr#edition_expand td.center, .search_form tr#edition_expand td.center, .breadcrumbs, #logchecker table.border td[colspan="2"], .votes_info_td, .drag_drop_save, #torrent_table td.small, .preview_submit {
  text-align: center;
}

#upload table#dnulist, #threadpoll #poll_container #poll.vote_form input[value="Vote"], #sortable_container, #top10 .thin > h3, #sortable_container ul#sortable, #upload .box.pad > h3 + p + p, #upload_table.create_form .layout.border.slice input#post {
  margin-top: 10px;
}

#upload #whmf_torrents > tr > td:first-child {
  width: 30%;
}

#upload #whmf_torrents tr .border.slice tr td textarea[name="release_desc"] {
  height: 75px;
}

#upload_table.create_form select {
  width: 130px;
}

#upload_table.create_form select#format, #upload_table.create_form select#bitrate, #upload_table.create_form select[name="media"], #upload_table.create_form select[name="releasetype"], #upload_table.create_form select#importance, #edition_information td.label {
  width: 110px;
}

#upload_table.create_form input#tags {
  width: 620px;
}

#upload_table.create_form .layout.border.slice table[style="margin-bottom: 2em;"] {
  margin-bottom: 0 !important;
}

#upload #content > .box.pad {
  margin: 0 !important;
  width: 100% !important;
}

#upload .box.pad > h3 + p {
  font-style: italic;
}

#upload .box.pad > h3 + p + p a, .stat, #vote_rankings.stats li {
  font-weight: bold;
}

#vanityhouse.torrent_table tr td {
  padding-left: 35px;
  border: none;
}

#vanityhouse.torrent_table tr {
  background-image: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/music.png");
  background-position: 0 5px;
  background-repeat: no-repeat;
}

#whmf_offer {
  width: 100%;
  margin: 10px 0 !important;
  border: none !important;
  font-weight: normal !important;
}

#whmf_offer span {
  font-weight: bold !important;
}

#whmf_offer ul {
  font-weight: normal !important;
}

#whmf_torrents .border.slice textarea[cols="30"] {
  width: 588px;
}

#whmf_torrents .border.slice .label, .forum_post .avatar img, .avatar, #friends .friends_table td:first-child img[width="50px"] {
  width: 120px !important;
}

#whmf_torrents .border.slice tr td:nth-child(2) {
  width: 80%;
  padding: 0;
  margin: 0;
}

#wiki .box.pad.center p {
  margin-bottom: 15px;
}

#wiki .add_form input[type="text"] {
  margin-right: 5px;
  padding-top: 6px;
  width: 175px;
  height: 12px;
}

#wiki .box.box_addalias > div, .rule_table, #requests .main_column .layout td > .edit_form, #whmf_torrents td[style="padding-left: 1em;"], #better .box.pad[style="padding: 10px 10px 10px 20px;"], #staff .thin > .box.pad {
  padding: 0 !important;
}

#wiki .sidebar .box.pad.center .search_form input[name="search"] {
  width: 216px;
}

#wiki table input[type="radio"] {
  top: 0;
}

#wiki input[value="Compare"] {
  margin: 10px 0 8px;
}

#wrapper {
  overflow: hidden;
  margin: 0 auto;
  min-width: 1000px;
  width: 100%;
}

#wrapper div::-webkit-scrollbar {
  width: 8px;
  height: 8px;
}

#wrapper div::-webkit-scrollbar-track {
  background-color: rgba(0, 0, 0, 0.12);
  -webkit-box-shadow: inset 0 0 2px black;
  box-shadow: inset 0 0 2px black;
}

#wrapper div::-webkit-scrollbar-track-piece {
  background-color: rgba(20, 20, 20, 0.4);
}

#wrapper div::-webkit-scrollbar-track-piece:start:hover, #wrapper div::-webkit-scrollbar-track-piece:end:hover {
  background-color: rgba(20, 20, 20, 0.2);
}

#wrapper div::-webkit-scrollbar-thumb {
  background-color: #2d2d2d;
  -webkit-box-shadow: inset 0 0 2px black;
}

#wrapper div::-webkit-scrollbar-thumb:hover, #wrapper div::-webkit-scrollbar-thumb:active {
  background-color: #2a2a2a;
}

#wrapper div::-webkit-scrollbar-button {
  width: 12px;
  height: 12px;
}

blockquote, #inbox .box.pad #preview {
  margin-top: 5px;
  padding: 10px;
  border: 1px solid #333;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  background-color: rgba(80, 80, 80, 0.2);
  text-align: justify;
}

textarea {
  resize: vertical;
}

select.ft_bitrate {
  width: 124px;
}

select.ft_hascue, select.ft_freetorrent, select.ft_format {
  width: 104px;
}

select.ft_releasetype {
  width: 102px;
}

select.ft_scene, select.ft_scene {
  width: 96px;
}

select#stylesheet {
  width: 108px;
}

select#friend {
  width: 150px;
  margin-right: 5px;
}

span.small_upvoted {
  display: inline-block;
  overflow: hidden;
  width: 16px;
  height: 14px;
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/notifications.png") no-repeat top left;
  background-position: 0px -62px;
  text-indent: 100%;
  white-space: nowrap;
  cursor: pointer;
}

span.small_downvoted {
  display: inline-block;
  overflow: hidden;
  width: 16px;
  height: 14px;
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/notifications.png") no-repeat top left;
  background-position: 0px -76px;
  text-indent: 100%;
  white-space: nowrap;
  cursor: pointer;
}

span.last_read a {
  display: block;
  margin: 0 0 0 5px;
  width: 20px;
  height: 20px;
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/goto.png") no-repeat center;
  background-position: bottom;
  background-size: 100%;
  opacity: 0.5;
}

span[style="float: right;"] > input[value="Preview"], span[style="float: right;"] > input[value="Post"] {
  margin-right: 6px;
}

input[type="text"], input[type="search"], input[type="password"], input[type="email"], input[type="url"], textarea {
  padding: 5px 10px;
  border: 1px solid #3B3B3B;
  background: rgba(0, 0, 0, 0.15);
  -webkit-box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  color: #9A9A9A;
  transition: .25s ease-in-out;
  -webkit-transition: .25s ease-in-out;
  -moz-transition: .25s ease-in-out;
  -o-transition: .25s ease-in-out;
}

input[type="checkbox"] {
  position: relative;
  display: inline-block;
  padding: 6px;
  border: 1px solid #3b3b3b;
  background: rgba(0, 0, 0, 0.15);
  -webkit-box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05), inset 0px -15px 10px -12px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  -webkit-appearance: none;
}

input[type="checkbox"]:active, input[type="checkbox"]:checked:active {
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05), inset 0px 1px 3px rgba(0, 0, 0, 0.1);
}

input[type="checkbox"]:checked {
  border: 1px solid #3b3b3b;
  background: rgba(0, 0, 0, 0.15);
  -webkit-box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05), inset 0px -15px 10px -12px rgba(0, 0, 0, 0.05), inset 15px 10px -12px rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  color: #3b3b3b;
}

input[type="checkbox"]:checked:after {
  position: absolute;
  top: -1px;
  left: 1px;
  color: #456478;
  content: '\2714';
  font-size: 12px;
}

input[type="radio"] {
  position: relative;
  top: 3px;
  display: inline-block;
  padding: 6px;
  border: 1px solid #3b3b3b;
  border-radius: 50px;
  background: rgba(0, 0, 0, 0.15);
  -webkit-box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05), inset 0px -15px 10px -12px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  -webkit-appearance: none;
}

input[type="radio"]:checked:after {
  position: absolute;
  top: 3px;
  left: 3px;
  width: 6px;
  height: 6px;
  border-radius: 50px;
  background: #456478;
  box-shadow: inset 0px 0px 10px rgba(0, 0, 0, 0.3);
  content: ' ';
  text-shadow: 0;
}

input[type="radio"]:checked {
  border: 1px solid #3b3b3b;
  background: rgba(0, 0, 0, 0.15);
  -webkit-box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05), inset 0px -15px 10px -12px rgba(0, 0, 0, 0.05), inset 15px 10px -12px rgba(255, 255, 255, 0.1), inset 0px 0px 10px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 0 5px rgba(0, 0, 0, 0.3);
  color: #456478;
}

input[type="radio"]:active, input[type="radio"]:checked:active {
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.05), inset 0px 1px 3px rgba(0, 0, 0, 0.1);
}

input[type="submit"], input[type="button"], button[type="button"], #upload #whmf_offer button, button#send_recommendation {
  display: inline-block;
  padding: 5px 10px;
  border: 1px solid #3b3b3b;
  background-color: #707070;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#333333), to(#181818));
  background-image: -webkit-linear-gradient(top, #333333, #181818);
  background-image: -moz-linear-gradient(top, #333333, #181818);
  background-image: -o-linear-gradient(top, #333333, #181818);
  background-image: linear-gradient(top bottom, #333333, #181818);
  color: #8b8b8b;
  text-decoration: none;
  text-shadow: 1px 1px 0px #333333;
  font-weight: bold;
}

input[type="submit"]:active, input[type="button"]:active, button[type="button"]:active, button#send_recommendation:active {
  background-color: #333333;
  background-image: -webkit-linear-gradient(top, #181818, #333333);
  background-image: -moz-linear-gradient(top, #181818, #333333);
  background-image: -o-linear-gradient(top, #181818, #333333);
  background-image: linear-gradient(to bottom, #181818, #333333);
}

input:focus, textarea:focus {
  outline: 0 !important;
  border: 1px solid #456478 !important;
  transition: .25s ease-in-out;
  -webkit-transition: .25s ease-in-out;
  -moz-transition: .25s ease-in-out;
  -o-transition: .25s ease-in-out;
}

input[value="Make Default"] {
  float: right;
  margin-right: 5px;
}

input#styleurl {
  width: 435px;
}

#user input[type="url"] {
  width: 513px;
}

tr.rowa:nth-child(n+2):hover, tr.rowb:nth-child(n+2):hover, #better tr:hover, tr.group_torrent:hover, #torrent_table tr.group:hover, #torrents .thin > table tr:nth-child(n+2):hover, #torrent_table tr.torrent:hover, #discog_table tr.discog:hover, #torrents_album tr.group:hover, #userhistory tr.group.discog:hover, .collage_table tr:nth-child(n+2):hover, .torrent_row:hover {
  background-color: rgba(50, 50, 50, 0.2);
}

tr#release_list td > input[type="checkbox"], tr#format_list td > input[type="checkbox"], tr#bitrate_list td > input[type="checkbox"], tr#media_list td > input[type="checkbox"] {
  margin: 2px;
}

td:last-child {
  border-right: none;
  border-bottom: none;
}

td:first-child {
  border-left: none;
}

tr:first-child td {
  border-top: none;
}

td {
  padding: 7px;
  border: 1px solid rgba(0, 0, 0, 0.1);
  text-align: left;
}

tr:last-child td, tr.group:last-child td {
  border-bottom: none;
}

td.colhead {
  margin: -11px;
  margin-bottom: 10px;
  padding: 8px !important;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#333333), to(#444444));
  background-image: -webkit-linear-gradient(top, #333333, #444444);
  background-image: -moz-linear-gradient(top, #333333, #444444);
  background-image: -o-linear-gradient(top, #333333, #444444);
  background-image: linear-gradient(top bottom, #333333, #444444);
  -webkit-box-shadow: inset 0 1px 0 rgba(25, 25, 25, 0.4);
  box-shadow: inset 0 1px 0 rgba(25, 25, 25, 0.4);
  color: #888 !important;
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.5);
}

td.unread, td.read, td.read_locked, td.unread_sticky, td.read_locked_sticky, td.unread_locked_sticky, td.read_sticky {
  width: 3.5%;
  height: 16px;
  background-position: center center;
  background-repeat: no-repeat;
}

td.unread {
  background-image: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/read.png");
  background-position: 3px center;
  border-left: 2px solid #528ba3;
}

td.read {
  background-image: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/unread.png");
}

td.read_locked {
  background-image: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/read-locked.png");
}

td.unread_sticky {
  background-image: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/sticky-read.png");
  background-position: 3px center;
  border-left: 2px solid #528ba3;
}

td.read_sticky {
  background-image: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/sticky-unread.png");
}

td.read_locked_sticky {
  background-image: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/sticky-unread-locked.png");
}

td.unread_locked_sticky {
  background-image: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/sticky-read-locked.png");
  background-position: 3px center;
  border-left: 2px solid #528ba3;
}

.navigation_list, .navigation_list ol {
  margin: 0 !important;
}

ol.navigation_list {
  margin: 0 0 0 25px !important;
  list-style-position: outside;
}

ul.collage_images {
  width: 710px !important;
}

ul.collage_images li {
  width: 142px !important;
  height: 142px !important;
}

ul.nobullet {
  list-style-type: none;
}

li.graph {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  margin: 2px 0px 10px 16px;
  padding: 3px;
  width: 80%;
  height: 15px;
  background: rgba(0, 0, 0, 0.25);
}

li.graph .center_poll {
  display: block;
  height: 7px;
  border: 1px solid #456478;
  background: #528ba3;
  -webkit-box-shadow: inset 0 -1px 1px #456478;
  box-shadow: inset 0 -1px 1px #456478;
}

.alertbar {
  padding: 0 5px;
}
.alertbar:last-child {
  margin-right: 55px;
}

.alertbar a[href*="torrents.php?action=notify"]:before, .alertbar a[href*="inbox.php"]:before, .alertbar a[href*="index.php"]:before, .alertbar a[href*="userhistory.php?action=subscribed_collages"]:before, .alertbar a[href="userhistory.php?action=quote_notifications"]:before, .alertbar a[href*="blog.php"]:before {
  position: relative;
  top: 3px;
  display: inline-block;
  margin: auto 5px auto auto;
  width: 16px;
  height: 13px;
  content: "";
  *top: 0;
}

.autocomplete-suggestions {
  background-color: rgba(32, 32, 32, 0.85);
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  border: 1px solid #3B3B3B;
}

.autocomplete-selected {
  background-color: rgba(100, 100, 100, 0.2);
}

.autocomplete-suggestions strong {
  color: #528ba3;
}

.avatar {
  max-width: 120px;
}

.bbcodes button {
  float: none !important;
  overflow: hidden;
  margin-top: 5px;
  width: 20px;
  height: 20px;
  border: 1px solid #1D1D1D !important;
  background-color: rgba(100, 100, 100, 0.6) !important;
  -webkit-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.15), inset -1px 1px 0 rgba(255, 255, 255, 0.12);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.15), inset -1px 1px 0 rgba(255, 255, 255, 0.12);
  color: #999 !important;
  text-shadow: none !important;
  font-size: 12px;
  cursor: pointer;
}

.bbcodes {
  padding: 2px !important;
}

.bookmark {
  height: 24px;
}

.box_lastfm #lastfm_stats ul.nobullet li {
  margin-left: 15px;
}

.box_lastfm #lastfm_stats li:last-child {
  margin: 0 0 5px !important;
}

.box.pad[style="padding: 20px 10px 10px 10px;"] {
  margin: 0 !important;
  padding: 0 !important;
}

.box2 {
  margin-bottom: 10px !important;
  padding: 10px !important;
  background-color: rgba(100, 100, 100, 0.15);
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  color: #9A9A9A;
}

.cats_col, .group.discog td.center:nth-child(2) {
  width: 25px;
}

.cats_music, .cats_comics, .cats_audiobooks, .cats_elearningvideos, .cats_comedy, .cats_applications, .cats_ebooks {
  margin: 0 !important;
  width: 25px !important;
  height: 25px !important;
}

.cats_music {
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/music.png");
}

.cats_comics {
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/comics.png");
}

.cats_audiobooks {
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/audiobooks.png");
}

.cats_elearningvideos {
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/elearning.png");
}

.cats_comedy {
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/comedy.png");
}

.cats_applications {
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/applications.png");
}

.cats_ebooks {
  background: url("https://raw.githubusercontent.com/WhatCD/Gazelle/master/static/styles/mono/icons/ebooks.png");
}

.debug_table {
  table-layout: fixed;
}

.edit_changelog textarea {
  width: 600px;
}

.edit_form input#yadg_input {
  width: 700px;
}

.field_div {
  margin-bottom: 10px;
}

.filter_torrents .cat_list td, .search_form .cat_list td, #manage_collage_table th {
  text-align: center;
}

.filter_torrents table:nth-child(2) td {
  padding: 8px 0 7px 0 !important;
  background-color: transparent;
}

.filter_torrents .cat_list[width="100%"] {
  border: none;
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}

.filter_torrents .submit {
  position: relative;
  height: 25px;
}

.filter_torrents .submit span {
  position: absolute;
  top: 4px;
  left: 65px;
  color: #666;
  font-size: 12px;
  line-height: 1.2em;
}

.filter_torrents .submit span:before {
  content: "(";
}

.filter_torrents .submit span:after {
  content: ")";
}

.forum_post li, .main_column li {
  margin-left: 15px;
}

.forum_post.box.vertical_margin div[style="float: right;"] input:nth-child(n+1), .box_tags .stats.nobullet div > a + a {
  margin-left: 3px;
}

.forum_post .avatar, #friends .friends_table td:first-child {
  padding: 10px;
  width: 100px !important;
  background-color: rgba(0, 0, 0, 0.12);
}

.forum_post .body {
  padding: 15px;
  line-height: 1.4em;
}

#forums .forum_post form textarea {
  width: 804px;
}

.forum_unread tr.colhead_dark td {
  background-image: -webkit-gradient(linear, left top, left bottom, from(#361c34), to(#191919)) !important;
  background-image: -webkit-linear-gradient(top, #361c34, #191919) !important;
  background-image: -moz-linear-gradient(top, #361c34, #191919) !important;
  background-image: -o-linear-gradient(top, #361c34, #191919) !important;
  background-image: linear-gradient(top bottom, #361c34, #191919) !important;
}

.friends_table textarea[cols="80"] {
  width: 715px;
}

.ft_cat_list {
  font-weight: bold;
}

.ft_artistname input, .ft_groupname input, #search_terms input, .ft_recordlabel input, .ft_filelist input, .ft_remasterrecordlabel input, #tagfilter input[type="text"], input#searchbox, input#username, #upload .thin > p input[type="text"], #user .send_form .layout.border input[name="email"], .search_form .layout input[size="60"], #wiki .thin > div > form > .layout.border input[size="70"] {
  width: 520px;
}

.ft_cataloguenumber, .ft_cataloguenumber input, .ft_remastertitle, .ft_remastertitle input, .ft_remastercataloguenumber input, #cataloguenumber_tr input, #oclc_tr input {
  width: 228px;
}

.ft_year input, .ft_remasteryear input, #year_tr input, #edition_year input {
  width: 75px;
}

.head, .colhead td, .colhead th, .recent .colhead td, .colhead_dark td, tr.colhead {
  margin: -10px;
  margin-bottom: 10px;
  padding: 8px 10px !important;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#1d1d1d), to(#191919));
  background-image: -webkit-linear-gradient(top, #1d1d1d, #191919);
  background-image: -moz-linear-gradient(top, #1d1d1d, #191919);
  background-image: -o-linear-gradient(top, #1d1d1d, #191919);
  background-image: linear-gradient(to bottom, #1d1d1d, #191919);
  text-shadow: 0.1em 0.1em rgba(0, 0, 0, 0.5);
  font-weight: bold;
}

.hidden {
  display: none !important;
}

.important_user, .sticky_post {
  border: 1px solid #3b3b3b;
}

.important_user .body {
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/op.png") no-repeat bottom right !important;
}

.important_text_alt {
  color: #428A42 !important;
}

.invitetree > ul ul {
  padding-left: 1rem;
}

.label, #searchthread .layout.border tr:nth-child(n+1) td:first-child, #newthreadtext td.label {
  width: 200px;
  text-align: right;
  font-weight: bold;
}

.layout.cat_list a.brackets {
  text-transform: capitalize;
}

.linkbox {
  margin-top: 10px;
  color: #444;
}

.linkbox, .notify_filter_links {
  margin-bottom: 10px;
  text-align: center;
  text-transform: capitalize;
}

.linkbox a {
  padding: 0 2px;
}

.brackets:before {
  content: "[";
  color: #444;
}

.brackets:after {
  content: "]";
  color: #444;
}

.nobr {
  white-space: nowrap;
}

.permission_container {
  float: left;
  width: 32%;
}

.permission_container:nth-child(2) {
  padding: 0px 2%;
}

.pressed {
  margin-top: 5px;
  width: 20px;
  height: 20px;
  background-color: rgba(100, 100, 100, 0.8) !important;
  -webkit-box-shadow: 0 1px 2px rgba(0, 0, 0, 0.15), inset -1px 1px 0 rgba(255, 255, 255, 0.12);
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.15), inset -1px 1px 0 rgba(255, 255, 255, 0.12);
  color: #eee !important;
  text-shadow: none !important;
  font-size: 12px;
  cursor: pointer;
}

.send_form textarea#quickpost[cols="90"], .edit_form textarea[cols="91"], #quickpost textarea#body, .box.pad .create_form textarea, .send_form textarea#message, #staffpm .manage_form textarea[cols="90"] {
  width: 958px !important;
  margin: 0;
}

.search_form input[type="checkbox"], #userform.edit_form input[type="checkbox"] {
  margin: -2px 2px 0 0;
  vertical-align: middle;
}

.sidebar input#filelist, .sidebar input#artistsimilar, .sidebar .add_form input[name="url"], .sidebar .box.box_addtag .add_form input[name="tagname"] {
  padding-top: 6px;
  width: 180px !important;
  height: 12px;
}

.sidebar .download_form select, .sidebar form[action="bookmarks.php"] select {
  width: 180px !important;
}

.sidebar .download_form input[value="Download"], .box_addartists input[value="Add"], .sidebar form[action="bookmarks.php"] input[value="Download"], .sidebar input#submit_button {
  margin-top: 5px;
  width: 100% !important;
}

.sidebar .box.box_addartists .add_form #AddArtists select {
  float: right;
  margin-top: 3px;
}

.sidebar .box.box_addartists .add_form #AddArtists input[name="aliasname[]"], #top10 tr.colhead_dark td:nth-child(4), #debug_flags .debug_flags_memory, .friends_table .left {
  width: 100px;
}

.size1 {
  font-size: 0.75em;
  line-height: 12px;
}

.size2 {
  font-size: 1em;
  line-height: 14px;
}

.size3 {
  font-size: 1.25em;
  line-height: 16px;
}

.size4 {
  font-size: 1.5em;
  line-height: 18px;
}

.size5 {
  font-size: 1.75em;
  line-height: 20px;
}

.size6 {
  font-size: 2em;
  line-height: 22px;
}

.size7 {
  font-size: 2.25em;
  line-height: 26px;
}

.size8 {
  font-size: 2.5em;
  line-height: 28px;
}

.size9 {
  font-size: 2.75em;
  line-height: 30px;
}

.size10 {
  font-size: 3em;
  line-height: 34px;
}

.snatched_group, .snatched_torrent {
  color: #6a6a6a;
  background-color: rgba(30, 30, 30, 0.5);
  border-left: 3px solid #4b4b4b;
}

.snatched_group .tags a, .snatched_torrent .tags a {
  color: #6a6a6a !important;
}

.snatched_group .show_torrents_link {
  background-position: -2px 0;
}

.snatched_group input[type="checkbox"], .unreadpm input[type="checkbox"] {
  margin-left: -2px;
}

.snatched_torrent td:first-child {
  padding-left: 4px;
}

/*
.snatched_group img, .snatched_torrent img {
    filter: url("data: image/svg+xml;
    utf8,<svg xmlns='http: //www.w3.org/2000/svg'><filter id='grayscale'><feColorMatrix type='matrix' values='0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0 0 0 1 0'/></filter></svg>#grayscale");
    filter: gray;
    filter: grayscale(100%);
    -webkit-filter: grayscale(100%);
    -moz-filter: grayscale(100%);
    -ms-filter: grayscale(100%);
    -o-filter: grayscale(100%);
    -webkit-filter: grayscale(1);
}

.snatched_group:hover img, .snatched_torrent:hover img {
    filter: none;
    -webkit-filter: grayscale(0);
    -moz-filter: grayscale(0);
    -ms-filter: grayscale(0);
    -o-filter: grayscale(0);
    border: 2px solid #528BA3 !important;
}
*/
.sticky_post .body {
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/sticky.png") no-repeat bottom right !important;
}

.tags {
  font-size: 11px;
  background: none !important;
}

.tags a, .tags a:visited {
  color: #777 !important;
}

.textarea_wrap textarea {
  width: 688px;
}

.thin > h2 + div > form table td.label {
  width: 20%;
}

.torrent span[style="float: right;"] {
  margin-top: 5px;
  margin-left: 20px;
}

.torrent_table, .request_table, .filelist_table, .forum_index, .subscribed_collages_table, .forum_post.box, #alerts, .layout, .message_table, .collage_table, #wiki form[action="wiki.php"] table, #reports .thin table, #reportsv2 .thin table, .friends_table, #whmf_torrents, .vote_matches_table, .torrentdetails.pad div table, #dnulist, #torrents .thin .header + table, #whmf_torrents .border.slice, #upload_table.create_form .textarea_wrap textarea, #userform.edit_form textarea#info, .box_addartists.box_addartists_similar .add_form, #userhistory table, #top10 h3 + .border, #torrents .thin.center > .box[style="width: 600px; margin: 0px auto;"], #user #content > .thin.center > .box {
  width: 100% !important;
}

/* Width 100% for elements */
.tl_approved, .invalid, .warning, .error, .new, .important_text, a[title="Delete Alias"], .remove a {
  color: #A33A3A !important;
}

.tl_free {
  color: #A7A45B;
}

.tl_neutral {
  color: #808080;
}

.tl_personal {
  color: #9751AD;
}

.tl_snatched {
  color: #4fa442;
}

.tl_reported {
  background-color: rgba(180, 75, 75, 0.5);
  color: #bababa;
  padding: 2px 3px;
  border-radius: 2px;
  font-size: 11px;
}

.favoritecount {
  color: #ddd;
  font-size: 11pt !important;
}

.unreadpm {
  background-color: rgba(50, 50, 50, 0.2);
  border-left: 3px solid #456478;
}

.votespan.brackets:before, .votespan.brackets:after {
  content: "";
}

.votespan {
  padding-right: 25px;
}

/* AAD Fix */
.group_image + .group_info {
  margin: 0;
  padding: 0 5px;
  display: table-cell;
  vertical-align: middle;
  height: 79px;
  width: 550px;
}

#artist .group_image + .group_info {
  width: 595px;
}

.group_image.float_left.clear img {
  height: 75px;
  width: 75px;
}

.group_image.float_left.clear img, #userhistory .torrent_table.grouped.artwork tr.group.discog td[style="width: 60px; padding: 0;"] img, #user .layout.recent a > img {
  border: 2px solid #3b3b3b !important;
}

.gm_albumartdisplay {
  width: 90px !important;
  height: 90px !important;
}

.gm_albumartdisplay img {
  width: 75px !important;
  height: 75px !important;
}

.gm_albumartdisplay_loading {
  background: transparent url("https://redacted.ch/static/styles/dark_mono_v2/img/progress.gif") no-repeat center center !important;
}

.gm_albumartdisplay img, #userhistory .torrent_table.grouped.artwork tr.group.discog td[style="width: 60px; padding: 0;"] img, #user .layout.recent a > img {
  margin: 5px;
  border: 2px solid #ccc !important;
}

.options_list li {
  margin: 5px 0;
}

.options_list li:first-child {
  margin-top: 0;
}

.options_list li:last-child {
  margin-bottom: 0;
}

/* Stylesheet gallery */
.preview_wrapper {
  margin: 0 7px;
  width: 30%;
}

.preview_image {
  width: 95%;
  overflow: hidden;
  opacity: 0.6;
  border: 2px solid #3b3b3b;
}

.preview_image:hover {
  border: 2px solid #528BA3;
  opacity: 1;
  transition: opacity .25s ease-in-out;
  -webkit-transition: opacity .25s ease-in-out;
  -moz-transition: opacity .25s ease-in-out;
  -o-transition: opacity .25s ease-in-out;
}

/* Tooltips */
.tooltipster-default {
  background-color: rgba(45, 45, 45, 0.95);
  border-color: rgba(0, 0, 0, 0.95);
  border-width: 1px;
  color: #9A9A9A;
  -webkit-box-shadow: 0px 2px 3px black;
  box-shadow: 0px 2px 3px rgba(0, 0, 0, 0.1);
}

.tooltipster-default .tooltipster-content {
  font-size: 12px;
  padding: 5px 8px;
  text-shadow: none;
}

/* Notifications */
#noty_bottomRight_layout_container > li {
  background-color: rgba(45, 45, 45, 0.85) !important;
  border-color: rgba(0, 0, 0, 0.95) !important;
  color: #9A9A9A !important;
}

.noty_bar div {
  background-color: inherit !important;
  border: 0 !important;
  color: inherit !important;
  font-size: 12px !important;
}

.noty_message {
  padding: 8px 10px 0px !important;
}

/* New user stuff */
.user_options .textarea_wrap {
  width: 486px;
}

.user_options hr {
  border-color: rgba(154, 154, 154, 0.75);
  border-width: 1px 0 0 0;
  border-style: solid;
}

#settings_sections h2 {
  font-size: 13px;
  line-height: 1.1em;
  margin-bottom: 0;
}

#settings_sections li {
  margin-bottom: 10px;
}

#settings_sections li:last-child {
  margin-bottom: 0;
}

/* Consistent .box and .pad rules */
#reportsv2 .pad, #reports .pad, .two_columns.pad {
  padding: 10px;
}

#reportsv2 .box, #reports .box {
  margin-bottom: 10px;
  background-color: rgba(100, 100, 100, 0.15);
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  color: #9A9A9A;
}

.snatches img {
  width: 15px;
  height: 15px;
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/snatched.png") no-repeat center;
}

.leechers img {
  width: 11px;
  height: 15px;
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/leechers.png") no-repeat center;
}

.seeders img {
  width: 11px;
  height: 15px;
  background: url("https://redacted.ch/static/styles/dark_mono_v2/img/seeders.png") no-repeat center;
}

/* Lightbox */
.blog_post img {
  max-width: 978px;
}

.forum_post td img {
  max-width: 828px;
}

.profileinfo img, #artist_information img, .box_request_desc img, .news_post img, .torrentdetails img, .torrent_description img, .wiki_article img {
  max-width: 700px;
}

.sidebar img {
  max-width: 230px;
}

#artistcomments img, #request_comments img, #torrent_comments img {
  max-width: 558px;
}

#artistcomments #reply_box img, #request_comments #reply_box img, #torrent_comments #reply_box img {
  max-width: 536px;
}

#collage #reply_box img, #forums #reply_box img {
  max-width: 806px;
}

#inbox #preview img, #staffpm #reply_box img, #wiki .create_form img, #wiki .edit_form img {
  max-width: 956px;
}

#inbox .body img {
  max-width: 978px;
}

#userform img {
  max-width: 490px;
}

#searchbars input {
  box-sizing: content-box;
}

tr.group {
  background: #1c1c1c;
}
tr.group .group_info {
  line-height: 1.6em;
}
tr.group .group_info a {
  font-weight: bold;
}
tr.group .tags {
  opacity: 0.6;
}
tr.group .tags a {
  font-weight: normal;
}

tr.group_torrent {
  font-size: 12px;
}
tr.group_torrent td.edition_info {
  background: #333333;
}

.news_post {
  line-height: 1.5em;
}

.r00 {
  color: #A33A3A;
}

.r01 {
  color: #FF1300;
}

.r02 {
  color: #FF1300;
}

.r03 {
  color: #FF2600;
}

.r04 {
  color: #FF4C00;
}

.r05 {
  color: #FF5E00;
}

.r06 {
  color: #FF5E00;
}

.r07 {
  color: #FF7100;
}

.r08 {
  color: #fd4337;
}

.r09 {
  color: #FA0;
}

.r10 {
  color: #74C42E;
}

.r20 {
  color: #418B00;
}

.r50 {
  color: #418B00;
}

.r99 {
  color: #418B00;
}

/*# sourceMappingURL=dark-mono-alt.css.map */
