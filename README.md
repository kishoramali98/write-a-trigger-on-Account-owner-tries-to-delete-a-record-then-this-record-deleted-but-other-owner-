# write-a-trigger-on-Account-owner-tries-to-delete-a-record-then-this-record-deleted-but-other-owner-
write a trigger on Account owner tries to delete a record then  this record deleted but other owner  not possible   show error "u can not delete record
pubiic static void restrictUser(list<Account> aacc)
{
   for(Account a:aacc)
    {
      id Usisd= userInfo.getuserId();
      a.addError(" sorry u r not delete record");
    }

}
