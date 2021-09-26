CMD:twitter(playerid, params[]){
    Dialog_Show(playerid, DIALOG_TW, DIALOG_STYLE_INPUT, "ทวิตเตอร์", "กรุณาใส่ข้อความ", "ส่ง", "ยกเลิก");
    return 1;
}

Dialog:DIALOG_TW(playerid, response, listitem, inputtext[]) {
    if (response)
    {
        new name[MAX_PLAYER_NAME + 1];
        GetPlayerName(playerid, name, sizeof name);

        if (isnull(inputtext))
            return Dialog_Show(playerid, DIALOG_TWITTER, DIALOG_STYLE_INPUT, "ทวิตเตอร์", "กรุณาใส่ข้อความ", "ส่ง", "ยกเลิก");

        SendClientMessageToAllEx(COLOR_WHITE, "{00BFFF}[Twitter] {FFFFFF} %s: %s", name, inputtext);
    }
    return 1;
}
