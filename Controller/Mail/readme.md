# Mail Class

> Handling mail data

## Method List

1. getFolder()
    > get folder list based user id
2. saveFolder($form_data)
    > add/update folder list
3. delFolder($folder_id)
    > delete folder
4. readFolder($input)
    > getting readFolder tree
5. getMailType($input)
    > getting mail type list
6. getMailCategory($input)
    > getting mail category
7. flagRead($tid)
    > updating mail mark as read
8. save($form_data)
    > save / update mail and send mail
9. delMail($m_id, $restore_folder_id)
    > delete mail data
10. setRead($m_id, $origin_folder)
    > updating read folder for read folder count
11. addRecipient($mail_id, $emp_id, $circulation)
    > append single recipient data
12. addMultiRecipients($mail_id, $emp_id, $circulation)
    > append multiple recipient data (checked emp)
13. delRecipient($id)
    > deleting recipient data
14. copyRecipient($new_mail_id, $ref_mail_id)
    > copy recipient from other mail (reply)
15. copyThreadRecipient($new_mail_id, $ref_mail_id)
    > copy recipient from other mail (reply to all linked recipient)
16. Recipient($input)
    > get or update recipient data
17. make_nlevel_threaded($src)
    > creating tree data from previous mail
18. find_node(&$dest, $row)
19. trackMail($input)
20. find($input)
21. move($form_data)
22. restore($m_id)
23. empty_trash()
24. getcounter()
