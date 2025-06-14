Notes on BR Uptakes for errors/warnings

This is the action chain that gets called during create/update button in panel drawer.

handleChangeBankAccountPopupActionChain
It takes actionType as input:
1.cancel - bankAccChangeWarnPopupCancelEvent  ,cancelBankAction
2.confirm - createEditDrawerSaveEvent, simpleCreateAndEditPageTemplateSpPrimaryAction
3.update - confirmBankUpdateAction , bankAccChangeWarnPopupConfirmEvent

\

bankPrePayWarnPopup
    :bankAccChangeWarnPopupConfirmEvent 
     bankAccChangeWarnPopupCancelEvent