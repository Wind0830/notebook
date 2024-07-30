```shell
mysqlbinlog --base64-output=decode-rows -v --database=bdp_worker_sge --start-datetime="2024-07-25 14:56:00" --stop-datetime="2024-07-25 14:56:59" /export/data/mysql/data/3306/binlog/mysql-bin.000560  > z
```
```text
DELETE FROM `bdp_worker_sge`.`sched_job`
### WHERE
###   @1=NULL
###   @2='TEST_0722_02'
###   @3='第二条用例'
###   @4='Pending'
###   @5='2024-07-21'
###   @6=''
###   @7=''
###   @8=NULL
###   @9=4
###   @10=NULL
###   @11='上游父作业数据日期不为Done'
###   @12='time'
###   @13='D'
###   @14='0'
###   @15=1
###   @16=150
###   @17=120
###   @18=NULL
###   @19=NULL
###   @20=NULL
###   @21=0
###   @22=3
###   @23=120
###   @24='1'
###   @25='0'
###   @26='0'
###   @27='0'
###   @28='0'
###   @29='ns_job'
###   @30=10
###   @31=''
###   @32=''
###   @33='test0002.sql'
###   @34='1'
###   @35='ocean'
###   @36=''
###   @37='4012-12-31 00:00:00'
###   @38=NULL
###   @39='ocean'
###   @40='2024-07-22 10:39:49'
###   @41=1721890559
###   @42=NULL
###   @43=NULL
###   @44='0'
###   @45='{"sqlRunner":"RUNNER_STINGER"}'
###   @46=NULL
###   @47='0'
###   @48=NULL
###   @49=NULL
###   @50=NULL

```