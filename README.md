public with sharing class AccountController {
  public static List<Account> getAllActiveAccounts() {
    return [SELECT Id,Name,Active__c FROM Account WHERE Active__c = 'Yes'];
    //This is the line add for Branch 1
<<<<<<< HEAD
    System.debug('FALSE');
=======
    System.debug('TRUE');
>>>>>>> origin/master
  }
}