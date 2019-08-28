# unixRecycle_Restore
Recycle script written in unix

If you don't want to commit to rm or rmdir here is a recycle bin script

Supports operands -v, -i, and -r for repositories

Will recursively recycle directories

Script uses readlink function, if using apple bash you'll need to implement 'greadlink' and update file accordingly

NOTE your recyclebin will be created in your home directory as well as a hidden restore info file

See restore repository to easily restore your file to it's original location with a restore script

USING SCRIPT:

  bash recycle <filename>
  OR
  sh recycle <filename>

   Operands
      -v
          Confirm's recycle
      -i
          Asks user to confirm file recycle
      -r
          Recursively recycles a diretory
      
  bash restore <filename>
  OR
  sh restore <filname>
      
