

ksh
export STOVDB=sto_dev
export NDTDB=ndt_dev
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_dev
export DBO=ndt
export PASSWORD=drei717
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log

ksh
export STOVDB=sto_tst
export NDTDB=ndt_tst
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log

ksh
export STOVDB=sto_hq
export NDTDB=ndt_hq
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_dev
export DBO=ndt
export PASSWORD=drei717
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log

ksh
export STOVDB=sto_do
export NDTDB=ndt_do
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_dev
export DBO=ndt
export PASSWORD=drei717
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log



ksh
export STOVDB=sto_be
export NDTDB=ndt_be
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log

ksh
export STOVDB=sto_dr
export NDTDB=ndt_dr
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log

ksh
export STOVDB=sto_fr
export NDTDB=ndt_fr
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log

ksh
export STOVDB=sto_ha
export NDTDB=ndt_ha
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log

ksh
export STOVDB=sto_mu
export NDTDB=ndt_mu
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log


ksh
export STOVDB=sto_ra
export NDTDB=ndt_ra
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log

ksh
export STOVDB=sto_st
export NDTDB=ndt_st
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log


ksh
export STOVDB=sto
export NDTDB=ndt
export OAPDB=oap
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
export DBTOOL=sqsh
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log



--Consumed for UAT Drop 1
ksh
export STOVDB=stoat
export NDTDB=ndtat
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log

--Consumed for UAT Drop 1
ksh
export STOVDB=stoat
export NDTDB=ndt_do
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_dev
export DBO=ndt
export PASSWORD=drei717
export TMPDIR=.
echo $STOVDB , $NDTDB , $DSQUERY , $DBO , $PASSWORD , $TMPDIR , $AMSDB , $SITEDB
make -s all 2>&1 | tee make_all_${DSQUERY}_${STOVDB}.log
make -s update 2>&1 | tee make_update_${DSQUERY}_${STOVDB}.log
make -s updstat 2>&1 | tee make_updstat_${DSQUERY}_${STOVDB}.log  
make -s grant 2>&1 | tee make_grant_${DSQUERY}_${STOVDB}.log
make -s correction 2>&1 | tee make_correction_${DSQUERY}_${STOVDB}.log


====================================================================================================================================================

ksh
export ATOLLDB_SM=stoatosm_dev
export ATOLLDB_CM=stoatocm_dev
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_dev
export NDTDB=ndt_dev
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_dev
export REGION=dev
export DBO=ndt
export PASSWORD=drei717
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &



ksh
export ATOLLDB_SM=stoatosm3120_710_tst
export ATOLLDB_CM=stoatocm3120_710_tst
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_tst
export NDTDB=ndt_tst
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export REGION=tst
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &



export ATOLLDB_SM=stoatosm3120_710_hq
export ATOLLDB_1M=stoato1m3120_710_hq
export ATOLLDB_2M=stoato2m3120_710_hq
export ATOLLDB_CM=stoatocm3120_710_hq
export STOVDB=sto_hq
export NDTDB=ndt_hq
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_dev
export REGION=hq
export DBO=ndt
export PASSWORD=drei717
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &

export ATOLLDB_SM=stoatosm3120_710_do
export ATOLLDB_CM=
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_do
export NDTDB=ndt_do
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_dev
export REGION=do
export DBO=ndt
export PASSWORD=drei717
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &

ksh
export ATOLLDB_SM=stoatosm3120_710_be
export ATOLLDB_CM=
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_be
export NDTDB=ndt_be
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export REGION=be
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &

ksh
export ATOLLDB_SM=stoatosm3120_710_dr
export ATOLLDB_CM=
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_dr
export NDTDB=ndt_dr
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export REGION=dr
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &

ksh
export ATOLLDB_SM=stoatosm3120_710_fr
export ATOLLDB_CM=
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_fr
export NDTDB=ndt_fr
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export REGION=fr
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &

ksh
export ATOLLDB_SM=stoatosm3120_710_ha
export ATOLLDB_CM=
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_ha
export NDTDB=ndt_ha
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export REGION=ha
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &

ksh
export ATOLLDB_SM=stoatosm3120_710_mu
export ATOLLDB_CM=
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_mu
export NDTDB=ndt_mu
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export REGION=mu
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &

ksh
export ATOLLDB_SM=stoatosm3120_710_ra
export ATOLLDB_CM=
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_ra
export NDTDB=ndt_ra
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export REGION=ra
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &

ksh
export ATOLLDB_SM=stoatosm3120_710_st
export ATOLLDB_CM=
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto_st
export NDTDB=ndt_st
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export REGION=st
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &
 
ksh
export ATOLLDB_SM=stoatosm
export ATOLLDB_CM=stoatocm
export ATOLLDB_1M=
export ATOLLDB_2M=
export STOVDB=sto
export NDTDB=ndt
export OAPDB=oap
export SITEDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.SITE"'"
export AMSDB="'"DC_ATOLL_DEV.ATOLL.AMS_O.v_ams_ant_master"'"
export DSQUERY=terndbs1_sql_tst
export REGION=PROD_TEST
export DBO=ndt
export PASSWORD=eins456
export TMPDIR=.
echo ${ATOLLDB_SM}, ${ATOLLDB_CM}, ${ATOLLDB_1M}, ${ATOLLDB_2M}, ${STOVDB}, ${NDTDB}, ${AMSDB} ,${SITEDB}, ${DSQUERY},${REGION},${DBO},${PASSWORD}
nohup make -s all 2>&1 | tee make_all_${DSQUERY}_${REGION}.log &
nohup make -s struct 2>&1 | tee make_struct_${DSQUERY}_${REGION}.log &
nohup make -s update 2>&1 | tee make_update_${DSQUERY}_${REGION}.log &
nohup make -s sync 2>&1 | tee make_sync_${DSQUERY}_${REGION}.log &
nohup make -s release 2>&1 | tee make_release_${DSQUERY}_${REGION}.log &



