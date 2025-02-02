# lo-list
 
```text
This tool is used to list buckets and objects in LUMI-O or Lumi-o. If bucket name is not defined, all buckets are listed.
If bucket name is defined, then objects inside the bucket are listed.



   lo-list <bucket_name>


Options:

-d  --dir               List content so that  / -characters on object names are used to define a directory structure.

-l, --lh <project_ID>   Print out detailed listing of the buckets or objects in a bucket.

-p, --prefix            List only objects starting with the given prefix.


Working with shared buckets:

                        When you list a contents of a bucket with lo-list, the command checks if the bucket used
                        belongs to the current project. If it does not belong to the project, the name of the shared
                        bucket is stored to LUMI-O or Lumi-o ( into object project-number-lo-tools/buckets_shared_to).
                        When you check the available buckets with command lo-list, the command shows also the names of
                        the shared buckets stored to LUMI-O or Lumi-o. NOTE that this option shows information about only about
                        shared buckets that have previously been used by lo-list. Thus you can't use lo-list check if some
                        new buckets has been shared to you.




Related commands: lo-put, lo-get, lo-delete, lo-find

```
