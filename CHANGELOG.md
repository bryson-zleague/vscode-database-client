# CHANGELOG

# 4.5.7 2022-2-6

- Support connect to redis with username.
- Auto scroll redis terminal.
- Copy ssh host if using ssh.
- Fix open es query not active connection #450.
- Better query file for table.

# 4.5.2 2022-1-21

- Add more error tolerance when connecting.
- Support show redis server version.
- Redis string key view support responsive.
- Fix join result causing the editor to disappear.
- Support special sftp root path.
- Remove ftp support.
- Hide ssh passphrase.
- SSH terminal add padding.
- Fix sqlite show name error.
- Fix sqlite complection fail.
- Other bugs fix.

# 4.5.0 2022-1-7

- Support connect to clickhouse.
- Show results in vertical direction.
- Using new empty row instead of dialog for insert data.
- Fix join result view and editor fail.
- Fix complection fail when has as keyword.

# 4.4.0 2021-12-30

- Update extension logo.
- Do not set the default statement timeout.

# 4.3.6 2021-12-25

- Update connect and result view some style.
- Redis show key count.
- Refresh column cache when click table.
- Import sql support multiple files.
- Sort mysql database name by alphabet.
- Change mysql column position add confirm.

# 4.3.5 2021-12-11

- Support delete multi redis key.
- Fix mysqldump8 dump mysql5.7 server fail.
- Fix complection fail when hidden procedure group.

# 4.3.1 2021-12-1

- Reduce mysql table info description.
- Reduce ssh connection description.
- Fix parse jsonb error #381.
- Fix redis change page size not work.

# 4.3.0 2021-11-29

- Improve tree view render performance.
- Update active connection icon.
- Support show redis database.
- Better result view design.
- Fix table columns complection fail.
- Fix not show call procedure result.
- Fix using ssh private key open terminal fail.
- Fix redis cluster load key fail.

# 4.2.3 2021-11-24

- Upgrade ssh2 version, now support more ssh private key format.
- Support connect postgresql and mysql by connectionUrl.
- Show postgresql and mysql version on panel.
- Fix result view not work on remote development.
- Fix postgresql not reload data when execute DML.

# 4.2.1 2021-11-22

- Using pg_dump to dump postgreSQL.
- Fix es load index fail.
- Fix socket path gone #364.
- Always open new ssh terminal and enhance key event dispath.
- Supports running in offline environment.
- Fix filter operation error.

# 4.2.0 2021-11-15

- Remove export file default path.

# 4.1.9 2021-11-11

- Using scan command instead keys for redis.
- Result and ssh terminal view font style follow vscode setting.
- Result view add sql preview feature.
- Better support for singe quote #341.

# 4.1.8 2021-10-29

- Better support for sqlite.
- Paste as plain text when edit on result view.
- Change filter operation from = to like.
- Support change default value for mysql #317.
- Change default dump url is workspace #293.
- Add more chinese support on web view.

# 4.1.7 2021-10-8

- Ignore ElasticSearch ssl certificate check.
- Fix show error column type on result view.
- Support config ssh connect timeout.
- Update result view filter color.
- Ftp node add refresh button.

# 4.1.6 2021-9-18

- Improve security, config.json will auto delete when close.
- Update some buttion border and icon.
- Add shortcut to run ElasticSearch query.
- Fix run postgresql explain sql fail.
- Fix show duplicate column nodes when have more constraint.
- Fix generate postgresql mock data fail.

# 4.1.5 2021-9-12

- Add pagination to view redis value with big data.
- Improve sql complection.
- Mongodb support sort by column.
- Change default export path as workspace.

# 4.1.3 2021-9-6

- Reduce ram usage for webview cache.

# 4.1.2 2021-8-29

- Better redis view.

# 4.1.0 2021-8-15

- Support connect to redis cluster, #242.
- Better result view .
- Export csv with header, #273.
- Fix result view loading state gone.
- Fix codelen check delimiter fail.
- Fix mysql8 cannot show index.

# 4.0.5 2021-8-13

- Struct sync remove disable connection.
- Fix auto complete fail on SQL file.
- Support close ssh connection.
- Fix result view border not fit for theme.`activeDocument`
- Fix untitle document cannot split.

# 4.0.0 2021-8-7

- Support multiple result view.
- Fix result view show vertical scrollbar.
- Fix conflict with other extension.
- Fix connect and result view legacy bugs.
- Remove native ssh from connect view.

# 3.9.9 2021-8-2

- Fix hover query table action not work.

# 3.9.8 2021-7-27

- Support special ssl ca certificate.
- Hover info add action to query table data.
- Fix complection bug.
- ElasticSearch support connect with token or account.
- Support connect by native ssh command.
- Fix open struct sync fail.

# 3.9.6 2021-7-22

- Add hover to run selected sql.
- Add sql template action icon to table node.

# 3.9.5 2021-7-19

- Using mysqldump to dump database.
- Fix connect to elasticsearch using ssh tunnel fail.
- Better postgresql support.

# 3.9.3 2021-7-2

- Better sql complection.
- Fix multi line space ignored.

# 3.9.2 2021-6-24

- Enhance sql detect.
- Update run query shortcut.
- Keep query file content.
- Create SQL document outline.

# 3.9.0 2021-6-22

- Support edit connection config.
- Isolate the configuration of vscode and ssh-remote.
- Support load data when load timeout.
- Support install sqlite3 from connect page.
- Better change active database item.
- Fix vscode shortcut not working on ssh terminal.
- Fix mongo export data fail.
- Update some ui.

# 3.8.9 2021-6-16

- Add shortcut of run sql on result view(ctrl+enter).
- Support generate database document.
- Fix bugs.

# 3.8.8 2021-6-11

- Fix date incorrect of sqlserver #199.
- Prefre using connection name #215.
- Postgresql query with quote #217.
- Fix export occur undefined #218.

# 3.8.7 2021-6-8

- Update toolbar style.
- Fix trigger template error.
- Support using sqlite3 from path.

# 3.8.6 2021-6-3

- Support connect redis with ssl.
- Fix parse empty string or zero as null on result.

# 3.8.3 2021-5-18

- Support connect to MongoDB.
- Fix postgresql duplicate tables.

# 3.8.2 2021-5-15

- Connection keep origin position when edit.
- Support export SQLite data and struct.
- Fix possible connection delete bug.

# 3.8.0 2021-5-14

- Support sqlite.
- SSH support download folder.

# 3.7.6 2021-5-12

- Update ui operation icon.
- Set ssh terminal as full height.
- Support open mysql and postgresql terminal.
- Fix some legacy bugs.

# 3.7.4 2021-5-11

- Support config ssl connection.
- Update ui operation icon.
- Better sql server support.
- Fix sqlserver cannot edit.
- Fix sqlserver show object source fail.

# 3.7.3 2021-5-9

- Compatible icon with version 1.56.0 of vscode.
- Fix include database not work.

# 3.7.2 2021-5-8

- Add cost time to result view.
- Fix ssh connnection private key not persist.
- Result show column type.

# 3.7.0 2021-5-7

- Fix struct sync open fail.
- Mssql add  windows auth option.
- Fix first data load fail.
- Trigger refresh when create object.
- Add run all sql comand.
- Format postgresql timestamp show like pgadmin4.

# 3.6.9 2021-4-28

- Support show multi DML execute result.
- Result view select column without '*'.
- Disable retry.
- Fix filter trigger save on result view.
- Update donate button style.

# 3.6.7 2021-4-2

- Postgresql support config ssl enable option.
- Support delimiter on codelen.
- Change ElasticSearch connect host:port to url.

# 3.6.5 2021-3-29

- Support connect to ftp server.
- Support delete ssh connection.
- Support show procedure one result.
- Fix bugs.

# 3.6.0 2021-3-11

- Support connect to database server without exists connection.
- Support connect to ssh server.
- Implment some ui feature of postgresql.

# 3.5.6 2021-3-7

- Redis Support add、delete of list、set、hash

# 3.5.5 2021-3-5

- Redis terminal support show some command.

# 3.5.3 2021-2-24

- SqlServer support change connection port.
- Fix postgresql import sql fail.
- Sort table by name.

# 3.5.2 2021-2-5

- Fix treeview not refresh when drop node.
- Result view update and get better update interactive.

# 3.5.0 2021-2-3

- Result View :
  - Adapt scroll bar when height change.
  - Move full button position.
  - Split only when run from editor
  - Fix elasticSearch query error message not showed
- Tree Ui :
  - Support hide userNode, viewNode.
  - Add some node info as tooltip.
  - Reduce connection name.
  - Support remember workspace connection status.
- Support sql intellisense cross schema.
- Update server status view.
- Support show postgresql, sqlserver schemas.

# 3.4.4 2021-1-29

- Support schema with postgresql、sqlserver.
- Design table view update.
- Add ui config
- Support config  connection timeout.

# 3.4.3 2021-1-28

- Fix new table panel cannot execute sql.
- Speed up data dump and support sqlserver、postgresql.
- Support disable sql code lens.
- Support connect to mssql with encrypt disabled.

# 3.3.4 2021-1-27

- Fix 3.3.1 add connection fail.
- Trim legacy code, better peformance right now.
- Add full result view icon.

# 3.3.1 2021-1-26

- More implement or table design.

# 3.3.0 2021-1-26

- Support close connection.
- Add snippet to sql editor.
- compatible with old vscode version.
- Fix code len detect comment as sql.
- Add context menu to result view.
- Add more chinese content.
- Init design table.

# 3.2.2 2021/1/25

- Fix redis folder Infinite recursion load bug.
- Add GUI of index manager view.
- Implement database struct sync feature.
- Enhance intetllisense sql.

# 3.2.1 2021/1/23

- Resign connect page.
- Add sql code lens.

# 3.2.0 2020/1/20

- Migrate elasticsearch node to nosql explorer.
- Support connect to redis server.

# 3.1.0 2021/1/17

- Support connect to elasticsearch.

# 3.0.0 2021/1/13

- Support connect to postgresql and sqlserver.
- Reduce resource consumption.
- Fix cannot edit json column data.

# 2.9.2 2021/1/4

- Better result view border color.
- Remember page size.
- Fix sql formatter could not be detect comment correctly.
- Add i18n of chinese.

# 2.9.0 2020/12/31

- Better update operation interactive.
- Support auto show total.
- Show column require hint.

# 2.8.9 2020/12/29

- Support export as csv、json.
- Enhance result UX.

# 2.8.8 2020/12/28

- Resign result page.

## 2.8.7 2020/12/22

- Resign connect page @donnisnoni.
- Reduce resource consumption when node change.
- Support save query as query node.

## 2.8.5 2020/12/6

- Add more feature to view node.
- Support change column position.

## 2.8 - 2020/11/29

- Support change active database from status bar.
- Support export view, procedure, function.
- Fix multi query page database change.
- Change mysql client to mysql2, now support mysql8.

## 2.7.5 - 2020/11/19

- Migrate status to status bar.

## 2.7.0 -2020/11/9

- Resule view theme follow vscode theme.

## 2.6.0 - 2020/10/20

- Support config connection per workspace.
- Hide error messages.

## 2.5.7 - 2020/9/21

- Refacotr export panel.

## 2.5.5 - 2020/9/6

- Change update as edit in same view.

## 2.5.0 - 2020/8/17

- Improvement query result render performance.

## 2.4.8 - 2020/8/14

- Fix new panel bug.

## 2.4.7 - 2020/8/13

- Fix overview render bug.

## 2.4.6 - 2020/8/11

- Add more keyword.

## 2.4.5 - 2020/8/10

- Support big number type.

## 2.4.3 - 2020/8/7

- Add database overview.
- Add diagram design.

## 2.4.2 - 2020/8/5

- Fix limit generator error.
- Adjust result page height.

## 2.4.0 - 2020/8/3

- Enhance dump performance.
- Refactor data import.

## 2.3.12 - 2020/8/3

- Auto add limit for select statement.

## 2.3.11 - 2020/8/2

- Hight light active connection.
- Show more info when open edit panel.
- Add column type tooltip in result panel.
- Fix copy fail.

## 2.3.7 - 2020/7/20

- Support config default limit of query.

## 2.3.6 - 2020/7/15

- Support edit date in result view.

## 2.3.5 - 2020/7/14

- Not record repeat history.
- Support query in new panel.
- Add count query to content menu of table node.
- Add truncate database to content menu of database node.

## 2.3.0 - 2020/7/10

- Update result view.

## 2.3.0 - 2020/7/8

- Add dark theme.

## 2.2.8 - 2020/7/7

- Add count button in view.

## 2.2.4~2.2.7

- Fix bugs and adjust result view.

## 2.2.3 - 2020/6/24

- Add copy host feature.
- Support add name prefix to connection.

## 2.2.0 - 2020/6/13

- Reduce package size.
- Support export data as xlsx.

## 2.1.4 - 2020/5/20

- Fix connect database by ssh tunnel fail.

## 2.1.0 - 2020/5/14

- Update Query Result Page

## 2.0.1 (2020/5/6)

- Highlight active database.
- Enhance dashboard.
- Support open table in new panel.

## 1.9.6 (2020/5/1)

- Fix bugs.

## 1.9.0 - 2020/4/28

- Support SSH tunel.
- Show comment of column、table on tree view.
- Suport export table struct.

## 1.8.1 - 2020/4/23

- Connect can specify database.
- Add mock data feature.
- Update mysql connect client to newest version.
- Fix inteliij bugs.

## 1.8.0 - 2020/4/22

- Show template sql in same file.
- Get connection correctly when connection multi server.
- Improve UI Interactive.
- Rollback when batch execute sql occur error.
- Fix bugs.

## 1.7.32 - 2020/4/18

- Fix legacy bug: connect to same host fail.

## 1.7.31 - 2020/4/17

- Switch active database using open query.
- support insert or update in any query result page.
- intellij insert|update code.
- show comment when edit.
- fix bugs.

## 1.7.2 - 2020/4/15

- Support copy database、table、column name
- Support show error message when importing data occur error.
- Remeber sql history for database
- Ui improve

## 1.7.1 - 2020/4/11

- Support sort、filter in result page.
- Enhance sql intelliCode.

## 1.7.0 - 2020/4/10

- Support Insert,Update,Delete in reuslt page.
- Refactoring event message.

## 1.6.37- 2020/3/20

- Table name inference
- Sql formatter
- Record History
- Import sql file
- Hover table to get info

## 1.6.36 - 2020/3/19

- Fix many mysql connection error.

## 1.6.35 - 2020/3/18

- get sql divisiton with semicolon on editor
- fix mysql 8.0 get function|procedure info fail.

## 1.6.2 (2020/3/9)

- Beautify query result page.

## 1.6.0 (2020/3/8)

- Fix refresh not update treeview
- Support operate user、trigger、view、procedure、function

## 1.5.4 (2020/3/7)

- Fix change database fail
- Query result page beautify
- Sql assistant enhance

## 1.5.3 - 2020/2/22

- Focus query result panel when query

## 0.3.0 (2018-03-12)

* Show query result as HTML table

## 0.2.3 (2018-02-23)

* Add support for executing selected query

## 0.2.2 (2017-12-31)

* [#10](https://github.com/formulahendry/vscode-mysql/issues/10): Add key bindings for 'Run MySQL Query'

## 0.2.1 (2017-12-05)

* Keep original properties when creating connection
* Close the connection after query

## 0.2.0 (2017-12-04)

* Support SSL connection

## 0.1.1 (2017-12-03)

* List columns

## 0.1.0 (2017-11-30)

* Support multiple statement queries

## 0.0.3 (2017-11-26)

* Activate extension when running MySQL query

## 0.0.2 (2017-11-24)

* Better output format: display output as table
* [#2](https://github.com/formulahendry/vscode-mysql/issues/2): Add option to set maximum table count, and increase the dafault count

## 0.0.1 (2017-11-22)

* Initial Release
