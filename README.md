# FireFox
自用 FireFox 脚本同步


/*==========标签设置========== Firefox61+ */

    user_pref("browser.tabs.animate", false);/*禁用标签动画效果*/
    user_pref("browser.search.openintab", true);//新标签页打开搜索栏
    user_pref("browser.urlbar.openintab", true);//地址栏新标签页打开
    user_pref("browser.tabs.loadInBackground", true);//在新标签页中打开链接，不立即切换
    user_pref("browser.tabs.loadDivertedInBackground",true);
    user_pref("browser.search.context.loadInBackground", true);
    user_pref("browser.tabs.loadBookmarksInTabs", true);/*新标签打开书签*/
    user_pref("browser.tabs.loadBookmarksInBackground", true);/*后台打开书签*/
    user_pref("browser.bookmarks.openInTabClosesMenu", false);/*中键单击书签不关闭*/
    user_pref("browser.tabs.closeWindowWithLastTab", false);/*关闭最后标签页不关闭浏览器*/
    user_pref("browser.link.open_external", 3);/*外部程序调用浏览器时新标签打开*/
    user_pref("browser.tabs.warnOnClose", false);/*关闭标签和窗口不提示*/
    user_pref("browser.tabs.warnOnCloseOtherTabs", false);/*关闭其他标签和窗口不提示*/
    user_pref("browser.warnOnQuit", false);/*退出浏览器时关闭所有标签和窗口不提示*/
    user_pref("browser.link.open_newwindow.restriction", 0);/*强制用新标签代替新窗口*/
