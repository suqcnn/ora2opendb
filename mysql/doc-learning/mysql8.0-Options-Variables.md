### MySQL8.0 Server and Status Variables and Options
--- 
+ Options and Variables Introduced in MySQL 8.0
+ Options and Variables Deprecated in MySQL 8.0
+ Options and Variables Removed in MySQL 8.0

---
#### 一、Options and Variables Introduced
+ **Acl_cache_items_count**：缓存的权限对象数，MySQL 8.0.0 
+ **Audit_log_current_size**：审计日志文件当前大小，MySQL 8.0.11
+ **Audit_log_event_max_drop_size**：删除最大的审计事件的大小，MySQL 8.0.11
+ **Audit_log_events**：已处理审计事件的数量，MySQL 8.0.11
+ **Audit_log_events_filtered**：过滤的审计事件数量，MySQL 8.0.11
+ **Audit_log_events_lost**：删除的审计事件数量，MySQL 8.0.11
+ **Audit_log_events_written**：记录的审计事件数量 ，MySQL 8.0.11
+ **Audit_log_total_size**：记录审计事件的总大小，MySQL 8.0.11
+ **Audit_log_write_waits**：延迟记录的审计事件数量 ，MySQL 8.0.11 
+ **Caching_sha2_password_rsa_public_key:**： caching_sha2_password认证插件RSA公钥值，MySQL 8.0.4 
+ **Com_alter_resource_group**：统计 ALTER RESOURCE GROUP 语句数量，MySQL 8.0.3
+ **Com_alter_user_default_role**：统计 ALTER USER ... DEFAULT ROLE 语句数量，MySQL 8.0.0
+ **Com_create_resource_group**：统计 CREATE RESOURCE GROUP 语句数量，MySQL 8.0.3
+ **Com_create_role**：统计 CREATE ROLE 语句数量，MySQL 8.0.0
+ **Com_drop_resource_group:**：统计 DROP RESOURCE GROUP 语句数量，MySQL 8.0.3
+ **Com_drop_role**：统计 DROP ROLE 语句数量，MySQL 8.0.0
+ **Com_grant_roles**：统计 GRANT ROLE 语句数量，MySQL 8.0.0
+ **Com_install_component**：统计 INSTALL COMPONENT 语句数量，MySQL 8.0.0
+ **Com_revoke_roles**：统计 REVOKE ROLES 语句数量，MySQL 8.0.0
+ **Com_set_resource_group:**：统计 SET RESOURCE GROUP 语句数量， MySQL 8.0.3
+ **Com_set_role**：统计 SET ROLE 语句数量，MySQL 8.0.0
+ **Com_uninstall_component**：统计 UINSTALL COMPONENT 语句数量，MySQL 8.0.0
+ **Connection_control_delay_generated:**：服务器延迟连接请求的次数，MySQL 8.0.1 
+ **Current_tls_ca**：ssl_ca 系统变量当前值，MySQL 8.0.16
+ **Current_tls_capath**：ssl_capath 系统变量当前值，MySQL 8.0.16
+ **Current_tls_cert**：ssl_cert 系统变量当前值，MySQL 8.0.16
+ **Current_tls_cipher**：ssl_cipher 系统变量当前值，MySQL 8.0.16
+ **Current_tls_ciphersuites**：tsl_ciphersuites 系统变量当前值，MySQL 8.0.16
+ **Current_tls_crl**：ssl_crl 系统变量当前值，MySQL 8.0.16
+ **Current_tls_crlpath**：ssl_crlpath 系统变量当前值，MySQL 8.0.16
+ **Current_tls_key**：ssl_key 系统变量当前值，MySQL 8.0.16
+ **Current_tls_version**：tls_version 系统变量当前值，MySQL 8.0.16
+ **Firewall_access_denied**：MySQL Enterprise Firewall 拒绝的语句数量，MySQL 8.0.11
+ **Firewall_access_granted**：MySQL Enterprise Firewall 接受的语句数量，MySQL 8.0.11
+ **Firewall_cached_entries**：MySQL Enterprise Firewall 记录的语句数量，MySQL 8.0.11
+ **Secondary_engine_execution_count**：未来使用，MySQL 8.0.13
+ **activate_all_roles_on_login**：是否在连接时激活所有用户角色，MySQL 8.0.2
+ **admin_address**：要绑定到管理接口上的连接的IP地址，MySQL 8.0.14
+ **admin_port**：用于管理接口连接的 TCP/IP 端口，MySQL 8.0.14
+ **audit-log**：是否激活审计日志插件，MySQL 8.0.11
+ **audit_log_buffer_size**：审计日志 buffer 大小，MySQL 8.0.11 
+ **audit_log_compression**：审计日志文件压缩方法，MySQL 8.0.11 
+ **audit_log_connection_policy**：连接相关事件的审计日志策略，MySQL 8.0.11 
+ **audit_log_current_session**：是否审计当前SESSION，MySQL 8.0.11
+ **audit_log_encryption**：审计日志文件加密方法，MySQL 8.0.11
+ **audit_log_exclude_accounts**：不审计账户，MySQL 8.0.11
+ **audit_log_file**：审计日志文件名，MySQL 8.0.11
+ **audit_log_filter_id**：当前审计日志过滤id，MySQL 8.0.11
+ **audit_log_flush**：关闭并重新打开审计日志文件，MySQL 8.0.11
+ **audit_log_format**：审计日志文件格式，MySQL 8.0.11
+ **audit_log_include_accounts**：审计账户，MySQL 8.0.11
+ **audit_log_policy**：审计日志策略，MySQL 8.0.11
+ **audit_log_read_buffer_size**：审计日志文件读缓冲区大小，MySQL 8.0.11
+ **audit_log_rotate_on_size**：在特定大小情况下关闭并重新打开审计日志文件，MySQL 8.0.11
+ **audit_log_statement_policy**：语句级相关事件审计日志策略，MySQL 8.0.11
+ **audit_log_strategy**：审计日志记录策略，MySQL 8.0.11
+ **authentication_ldap_sasl_auth_method_name:**：认证方法名，MySQL 8.0.11
+ **authentication_ldap_sasl_bind_base_dn**：LDAP服务基础专有名称，MySQL 8.0.11
+ **authentication_ldap_sasl_bind_root_dn**：LDAP服务根专有名称，MySQL 8.0.11
+ **authentication_ldap_sasl_bind_root_pwd**：LDAP服务根绑定密码，MySQL 8.0.11
+ **authentication_ldap_sasl_ca_path**：LDAP服务证书颁发机构文件名，MySQL 8.0.11
+ **authentication_ldap_sasl_group_search_attr**：LDAP服务组搜索属性，MySQL 8.0.11
+ **authentication_ldap_sasl_group_search_filter**：LDAP自定义组搜索过滤器，MySQL 8.0.11
+ **authentication_ldap_sasl_init_pool_size**：LDAP服务初始化连接池大小，MySQL 8.0.11
+ **authentication_ldap_sasl_log_status**：LDAP服务日志级别，MySQL 8.0.11
+ **authentication_ldap_sasl_max_pool_size**：LDAP服务最大连接池大小，MySQL 8.0.11
+ **authentication_ldap_sasl_server_host**：LDAP服务主机名或者ip地址，MySQL 8.0.11
+ **authentication_ldap_sasl_server_port**：LDAP服务端口号，MySQL 8.0.11
+ **authentication_ldap_sasl_tls**：到LDAP服务是否使用加密连接，MySQL 8.0.11
+ **authentication_ldap_sasl_user_search_attr**：LDAP服务用户搜索属性，MySQL 8.0.11
+ **authentication_ldap_simple_auth_method_name**：认证方法名，MySQL 8.0.11
+ **authentication_ldap_simple_bind_base_dn**：LDAP服务基础专有名称，MySQL 8.0.11
+ **authentication_ldap_simple_bind_root_dn**：LDAP服务根专有名称，MySQL 8.0.11
+ **authentication_ldap_simple_bind_root_pwd**：LDAP服务根绑定地址，MySQL 8.0.11
+ **authentication_ldap_simple_ca_path**：LDAP服务证书颁发机构文件名，MySQL 8.0.11
+ **authentication_ldap_simple_group_search_attr**：LDAP服务组搜索属性，MySQL 8.0.11
+ **authentication_ldap_simple_group_search_filter**：LDAP自定义组搜索过滤，MySQL 8.0.11
+ **authentication_ldap_simple_init_pool_size**：LDAP服务初始化连接池大小，MySQL 8.0.11
+ **authentication_ldap_simple_log_status**：LDAP服务日志级别，MySQL 8.0.11
+ **authentication_ldap_simple_max_pool_size**：LDAP服务最大连接池大小，MySQL 8.0.11
+ **authentication_ldap_simple_server_host**：LDAP服务主机名或者ip地址，MySQL 8.0.11
+ **authentication_ldap_simple_server_port**：LDAP服务端口号，MySQL 8.0.11
+ **authentication_ldap_simple_tls**：到LDAP服务是否使用加密连接，MySQL 8.0.11
+ **authentication_ldap_simple_user_search_attr**：LDAP服务用户搜索属性，MySQL 8.0.11
+ **authentication_windows_log_level**：Windows认证插件日志级别，MySQL 8.0.11
+ **authentication_windows_use_principal_name**：是否使用Windows身份验证插件主体名称，MySQL 8.0.11
+ **binlog_encryption**：对二进制日志文件和relay log日志文件进行加密， MySQL 8.0.14
+ **binlog_expire_logs_seconds**：多少秒后清理二进制日志文件，MySQL 8.0.1
+ **binlog_rotate_encryption_master_key_at_startup**：在服务启动时，轮转加密二进制日志文件master key值，MySQL 8.0.14
+ **binlog_row_event_max_size**：二进制日志文件最大事件大小，MySQL 8.0.14
+ **binlog_row_metadata**：使用RBR时，配置表相关的二进制日志的元数据量，MySQL 8.0.1
+ **binlog_row_value_options**：基于RBR的复制，启用二进制日志文件记录部分JSON更新，MySQL 8.0.3
+ **binlog_transaction_dependency_history_size**：搜索从上次更新以来保留的row hashes事务数，MySQL 8.0.1
+ **binlog_transaction_dependency_tracking**：依赖关系信息的来源（提交时间戳或事务写入集），用于评估Slave的多线程应用程序可以并行执行哪些事务。，MySQL 8.0.1
+ **caching_sha2_password_auto_generate_rsa_keys**：是否自动生成RSA key文件，MySQL 8.0.4
+ **caching_sha2_password_private_key_path**：SHA2认证插件私钥路径名，MySQL 8.0.3
+ **caching_sha2_password_public_key_path**：SHA2认证插件公钥路径名，MySQL 8.0.3
+ **connection_control_failed_connections_threshold**：在延迟发生之前连续失败的连接尝试，MySQL 8.0.1
+ **connection_control_max_connection_delay**：服务器响应失败连接重试的最大延迟（ms），MySQL 8.0.1
+ **connection_control_min_connection_delay**：服务器响应失败连接重试的最小延迟（ms），MySQL 8.0.1
+ **create_admin_listener_thread**：在管理接口是否连接使用专用监听线程，MySQL 8.0.14
+ **cte_max_recursion_depth**：CTE最大递归深度，MySQL 8.0.3
+ **ddl-rewriter**：是否激活ddl_rewriter插件，MySQL 8.0.16
+ **default_collation_for_utf8mb4**：utf8mb4字符集的默认校验规则，MySQL 8.0.11
+ **default_table_encryption**：schema和tablespace默认加密设置，MySQL 8.0.16 
+ **dragnet.Status**：dragnet.log_error_filter_rules最新结果，MySQL 8.0.12
+ **dragnet.log_error_filter_rules**：错误日志过滤规则，MySQL 8.0.4
+ **early-plugin-load**：在加载强制内置插件之前和存储引擎初始化之前指定要加载的插件，MySQL 8.0.0
+ **group_replication_autorejoin_tries**：成员自动重新键入组尝试的次数，MySQL 8.0.16
+ **group_replication_communication_debug_options**：组复制组件Debug信息的级别，MySQL 8.0.3
+ **group_replication_communication_max_message_size**：组复制通信的最大消息大小，更大的消息会碎片化，MySQL 8.0.16
+ **group_replication_consistency**：组提供的事务一致性保证类型，MySQL 8.0.14 
+ **group_replication_exit_state_action**：实例在不自觉地离开组时的行为方式，MySQL 8.0.12 
+ **group_replication_flow_control_hold_percent**：定义未使用的组配额的百分比，MySQL 8.0.2 
+ **group_replication_flow_control_max_commit_quota**：定义组的最大流量控制配额，MySQL 8.0.2
+ **group_replication_flow_control_member_quota_percent**：：定义计算配额时成员应该假定的配额百分比，MySQL 8.0.2
+ **group_replication_flow_control_min_quota**：控制可分配给成员的最低流量控制配额，MySQL 8.0.2
+ **group_replication_flow_control_min_recovery_quota**：控制由于组中的另一个恢复成员而可以分配给成员的最低配额，MySQL 8.0.2
+ **group_replication_flow_control_period**：定义流控制迭代之间等待的秒数，MySQL 8.0.2 
+ **group_replication_flow_control_release_percent**：：定义当流控制不再需要限制编写器成员时应如何释放组配额，MySQL 8.0.2
+ **group_replication_member_expel_timeout**：组成员被怀疑失败并被驱逐出组之间的时间，导致组成员身份重新配置，MySQL 8.0.13
+ **group_replication_member_weight**：该成员被选为主要成员 primary 的机会，MySQL 8.0.2.
+ **group_replication_message_cache_size**：组通信引擎（XCom）中的消息缓存的最大内存，MySQL 8.0.16
+ **group_replication_recovery_get_public_key**：是否接受从master获取公钥的首选项，MySQL 8.0.4
+ **group_replication_recovery_public_key_path**：接受公钥信息，MySQL 8.0.4
+ **group_replication_unreachable_majority_timeout**：等待导致少数群体离开群组的网络分区需要多长时间，MySQL 8.0.2
+ **histogram_generation_max_mem_size**：创建直方图统计信息所需最大内存，MySQL 8.0.2
+ **immediate_server_version**：作为复制拓扑中的直接主服务器的服务器的MySQL服务器版本号，MySQL 8.0.14 
+ **information_schema_stats_expiry**：缓存表统计信息的过期设置，MySQL 8.0.3
+ **innodb_buffer_pool_debug**：当innodb_buffer_pool_size小于1G时，允许多少个buffer pool实例，MySQL 8.0.0
+ **innodb_buffer_pool_in_core_file**：控制将缓冲池页面写入核心文件 ，MySQL 8.0.14 
+ **innodb_checkpoint_disabled**： 禁用检查点，以便服务器退出时总是启动恢复，MySQL 8.0.2
+ **innodb_ddl_log_crash_reset_debug**： 重置DDL日志崩溃注入计数器的debug选项，MySQL 8.0.3
+ **innodb_deadlock_detect**：启用或者禁用死锁检测，MySQL 8.0.0 
+ **innodb_dedicated_server**：启用自动配置buffer pool大小, 日志文件大小和刷线方法，MySQL 8.0.3 
+ **innodb_directories**：定义服务启动时扫描的表空间数据文件的目录，MySQL 8.0.4
+ **innodb_fsync_threshold**：创建新文件时，控制何时Innodb调用fsync，MySQL 8.0.13
+ **innodb_log_checkpoint_fuzzy_now**：强制Innodb写fuzzy检查点的debug选项，MySQL 8.0.13 
+ **innodb_log_spin_cpu_abs_lwm**：低于用户线程在等待刷新redo不再旋转时的最小CPU使用量，MySQL 8.0.11 
+ **innodb_log_spin_cpu_pct_hwm**：高于用户线程在等待刷新redo不再旋转时的最大CPU使用量，MySQL 8.0.11 
+ **innodb_log_wait_for_flush_spin_hwm**：高于用户线程在等待刷新redo不再旋转时最大平均日志刷新时间 ，MySQL 8.0.11  
+ **innodb_parallel_read_threads**：并行索引读的线程数量，MySQL 8.0.14 
+ **innodb_print_ddl_logs**：是否打印DDL日志到错误日志文件中，MySQL 8.0.3 
+ **innodb_redo_log_encrypt**：控制加密表空间的重做日志数据的加密，MySQL 8.0.1
+ **innodb_scan_directories**：定义在InnoDB恢复期间扫描表空间文件的目录，MySQL 8.0.2
+ **innodb_spin_wait_pause_multiplier**：定义乘数值，用于确定旋转等待循环中的PAUSE指令数，MySQL 8.0.16 
+ **innodb_stats_include_delete_marked**：计算持久的InnoDB统计信息时，包括删除标记的记录 ，MySQL 8.0.1 
+ **innodb_temp_tablespaces_dir**：会话临时表空间路径 ，MySQL 8.0.13
+ **innodb_tmpdir**： 在线 ALTER TABLE 操作，临时表文件创建的目录位置，MySQL 8.0.0 
+ **innodb_undo_log_encrypt**：控制加密表空间的撤消日志数据的加密，MySQL 8.0.1 
+ **internal_tmp_mem_storage_engine**：定义内部内存临时表的存储引擎，MySQL 8.0.2 
+ **keyring-migration-destination**：秘钥迁移目标keyring插件 ，MySQL 8.0.4  
+ **keyring-migration-host**：用于连接到运行服务器以进行密钥迁移的主机名，MySQL 8.0.4   
+ **keyring-migration-password**：用于连接到运行服务器以进行密钥迁移的密码，MySQL 8.0.4   
+ **keyring-migration-port**：用于连接到运行服务器以进行密钥迁移的TCP/IP端口号，MySQL 8.0.4 
+ **keyring-migration-socket**：用于连接到运行服务器以进行密钥迁移的Unix的socket文件或者Windows的命名管道，MySQL 8.0.4
+ **keyring-migration-source**：密钥迁移的源端keyring插件，MySQL 8.0.4    
+ **keyring-migration-user**：用于连接到运行服务器以进行密钥迁移的用户名，MySQL 8.0.4  
+ **keyring_aws_cmk_id**：AWS keyring插件 客户主密钥ID值，MySQL 8.0.11  
+ **keyring_aws_conf_file**：AWS keyring插件 配置文件位置，MySQL 8.0.11 
+ **keyring_aws_data_file**：AWS keyring插件 存储文件位置，MySQL 8.0.11 
+ **keyring_aws_region**：AWS keyring插件区域，MySQL 8.0.11 
+ **keyring_encrypted_file_data**：keyring_encrypted_file 插件数据文件 ，MySQL 8.0.11 
+ **keyring_encrypted_file_password**：keyring_encrypted_file 插件密码，MySQL 8.0.11
+ **keyring_okv_conf_dir**：Oracle Key Vault keyring 插件配置目录，MySQL 8.0.11 
+ **keyring_operations**：是否启用keyring操作，MySQL 8.0.4 
+ **lock_order**：是否在运行时启用LOCK_ORDER工具，MySQL 8.0.17 
+ **lock_order_debug_loop**：当LOCK_ORDER工具遇到标记为循环的依赖项时是否导致调试断言，MySQL 8.0.17
+ **lock_order_debug_missing_arc**：当LOCK_ORDER工具遇到未声明的依赖项时是否导致调试断言，MySQL 8.0.17 
+ **lock_order_debug_missing_key**：当LOCK_ORDER工具遇到没有使用性能模式正确检测的对象时是否导致调试断言，MySQL 8.0.17 
+ **lock_order_debug_missing_unlock**当LOCK_ORDER工具遇到仍然保持时被销毁的锁时，是否导致调试断言，MySQL 8.0.17 
+ **lock_order_dependencies**：lock_order_dependencies.txt 文件的路径，MySQL 8.0.17 
+ **lock_order_extra_dependencies**：第二个依赖项文件的路径，MySQL 8.0.17 
+ **lock_order_output_directory**：LOCK_ORDER工具写入日志的目录，MySQL 8.0.17 
+ **lock_order_print_txt**：是否执行锁定顺序图分析和打印文本报告，MySQL 8.0.17 
+ **lock_order_trace_loop**：当LOCK_ORDER工具遇到标记为循环的依赖项时是否打印日志文件跟踪， MySQL 8.0.17 
+ **lock_order_trace_missing_arc**：当LOCK_ORDER工具遇到未声明的依赖项时是否打印日志文件跟踪， MySQL 8.0.17 
+ **lock_order_trace_missing_key**：当LOCK_ORDER工具遇到没有使用性能模式正确检测的对象时是否打印日志文件跟踪， MySQL 8.0.17
+ **lock_order_trace_missing_unlock**：是否在LOCK_ORDER工具遇到仍然保持时销毁的锁时打印日志文件跟踪，MySQL 8.0.17 
+ **log_error_filter_rules**：错误日志过滤规则，MySQL 8.0.2 
+ **log_error_services**：错误日志使用组件，MySQL 8.0.2 
+ **log_error_suppression_list**：错误日志中禁止的 警告/信息，MySQL 8.0.13 
+ **log_slow_extra**：是否写额外的信息到slow log中，MySQL 8.0.14 
+ **mandatory_roles**：自动为所有用户授予的权限，MySQL 8.0.2 
+ **mysql_firewall_mode**：MySQL Enterprise Firewall是否可以运行，MySQL 8.0.11 
+ **mysql_firewall_trace**：是否启用防火墙跟踪，MySQL 8.0.11 
+ **mysqlx**：是否初始化 X 插件，MySQL 8.0.11
+ **mysqlx_interactive_timeout**：等待交互式客户端超时的秒数，MySQL 8.0.4 
+ **mysqlx_read_timeout**：等待阻止读取操作完成的秒数，MySQL 8.0.4
+ **mysqlx_wait_timeout**：等待连接活动的秒数，MySQL 8.0.4 
+ **mysqlx_write_timeout**：等待阻止写入操作完成的秒数，MySQL 8.0.4 
+ **named_pipe_full_access_group**：授予对命名管道的完全访问权限的Windows组的名称，MySQL 8.0.14 
+ **no-dd-upgrade**：防止在启动时自动升级数据字典表，MySQL 8.0.4 
+ **no-monitor**：RESTART需要的监视进程不fork，MySQL 8.0.12 
+ **original_commit_timestamp**：在原始主服务器上提交事务的时间，MySQL 8.0.1
+ **original_server_version**：最初提交事务的服务器的MySQL Server版本号，MySQL 8.0.14
+ **partial_revokes**：是否启用部分撤销，MySQL 8.0.16 
+ **password_history**：密码重用前所需的密码更改次数，MySQL 8.0.3 
+ **password_require_current**：密码更改是否需要当前密码验证，MySQL 8.0.13
+ **password_reuse_interval**：密码重用之前所需的天数，MySQL 8.0.3 
+ **performance_schema_max_digest_sample_age**：查询以秒为单位重新采样年龄，MySQL 8.0.3
+ **persist_only_admin_x509_subject**：SSL证书X.509启用持久限制的系统变量的主题，MySQL 8.0.14 
+ **persisted_globals_load**：是否加载持久配置设置，MySQL 8.0.0
+ **print_identified_with_as_hex**：对于SHOW CREATE USER，打印包含十六进制不可打印字符的哈希值，MySQL 8.0.17
+ **regexp_stack_limit**：正则表达式匹配堆栈大小限制，MySQL 8.0.4
+ **regexp_time_limit**：正则表达式匹配超时，MySQL 8.0.4
+ **resultset_metadata**：服务器是否返回结果集元数据，MySQL 8.0.3
+ **rpl_read_size**：设置从二进制日志文件和中继日志文件中读取的最小数据量（以字节为单位），MySQL 8.0.11 
+ **secondary_engine_cost_threshold**：未来使用，MySQL 8.0.16
+ **show_create_table_verbosity**：SHOW CREATE TABLE 是否显示ROW_FORMAT，即使有默认值，MySQL 8.0.11
+ **sql_require_primary_key**：表是否必须有主键，MySQL 8.0.13
+ **ssl_fips_mode**：服务端是否启用FIPS模式，MySQL 8.0.11 
+ **syseventlog.facility**：系统日志消息的工具，MySQL 8.0.13
+ **syseventlog.include_pid**：syslog日志信息中是否包含server PID，MySQL 8.0.13
+ **syseventlog.tag**：在syslog消息中标记服务器标识符，MySQL 8.0.13 
+ **table_encryption_privilege_check**：启用TABLE_ENCRYPTION_ADMIN权限检查，MySQL 8.0.16
+ **temptable_max_ram**：定义数据存储在磁盘上之前TempTable存储引擎可占用的最大内存量，MySQL 8.0.2
+ **temptable_use_mmap**：定义TempTable存储引擎在达到temptable_max_ram阈值时是否分配内存映射文件，MySQL 8.0.16
+ **thread_pool_algorithm**：线程池算法，MySQL 8.0.11
+ **thread_pool_high_priority_connection**：当前会话是否是高优先级，MySQL 8.0.11 
+ **thread_pool_max_unused_threads**：未使用线程的最大允许数量，MySQL 8.0.11
+ **thread_pool_prio_kickup_timer**：将语句移动到高优先级执行之前多长时间，MySQL 8.0.11
+ **thread_pool_size**：线程池中线程组的数量，MySQL 8.0.11
+ **thread_pool_stall_limit**：声明被定义为停滞多久之前，MySQL 8.0.11
+ **tls_ciphersuites**：允许加密连接的TLSv1.3密码套件，MySQL 8.0.16
+ **upgrade**：控制服务启动时自动升级，MySQL 8.0.16
+ **use_secondary_engine**：未来使用，MySQL 8.0.13
+ **validate-config**：验证服务配置，MySQL 8.0.16
+ **validate_password.check_user_name**：是否根据用户名检查密码，MySQL 8.0.4
+ **validate_password.dictionary_file**：validate_password字典文件，MySQL 8.0.4 
+ **validate_password.dictionary_file_last_parsed:**：上次解析字典文件时间，MySQL 8.0.4
+ **validate_password.dictionary_file_words_count**：字典文件中的单词数，MySQL 8.0.4 
+ **validate_password.length**：validate_password需要的密码长度，MySQL 8.0.4
+ **validate_password.mixed_case_count**：validate_password需要的大写/小写字符的数量，MySQL 8.0.4 
+ **validate_password.number_count**：validate_password需要的数字字符数，MySQL 8.0.4 
+ **validate_password.policy**：validate_password密码策略，MySQL 8.0.4
+ **validate_password.special_char_count**：validate_password需要特殊字符的数量，MySQL 8.0.4
+ **version_compile_zlib**：编译的zlib库的版本，MySQL 8.0.11
+ **windowing_use_high_precision**：是否以高精度计算窗口函数，MySQL 8.0.2

---
#### 二、Options and Variables Deprecated
+ **expire_logs_days**：清理二进制日志时间周期，MySQL 8.0.3
+ **innodb_undo_tablespaces**：回滚段表空间文件数量，MySQL 8.0.4
+ **log_syslog**：是否将错误日志写入syslog，MySQL 8.0.2
+ **no-dd-upgrade**：阻止启动时自动升级数据字典表，MySQL 8.0.16
+ **symbolic-links**：允许MyISAM表建立符号链接，MySQL 8.0.2 

---
#### 三、Options and Variables Removed
+ **Com_alter_db_upgrade**：统计ALTER DATABASE ... UPGRADE DATA DIRECTORY NAME语句数量，MySQL 8.0.0
+ **Innodb_available_undo_logs**：显示InnoDB回滚段的总数量，不同于innodb_rollback_segments变量（显示活跃的回滚段数量），MySQL 8.0.2
+ **Qcache_free_blocks**：查询缓存（QC）中的可用内存块数，MySQL 8.0.3
+ **Qcache_free_memory**：查询缓存（QC）的可用内存量，MySQL 8.0.3
+ **Qcache_hits**：查询缓存（QC）命中数，MySQL 8.0.3
+ **Qcache_inserts**：查询缓存（QC）插入的数量，MySQL 8.0.3
+ **Qcache_lowmem_prunes**：由于缓存中缺少可用内存而从查询缓存（QC）中删除的查询数，MySQL 8.0.3
+ **Qcache_not_cached**：非缓存查询（QC）的数量（由于query_cache_type设置而无法缓存或未缓存），MySQL 8.0.3
+ **Qcache_queries_in_cache**：在查询缓存（QC）中注册的查询数，MySQL 8.0.3
+ **Qcache_total_blocks**：查询缓存（QC）中的块总数，MySQL 8.0.3
+ **Slave_heartbeat_period**：Slave库复制心跳间隔，单位：秒，MySQL 8.0.1
+ **Slave_last_heartbeat**：以TIMESTAMP格式显示收到最新心跳信号的时间，MySQL 8.0.1
+ **Slave_received_heartbeats**：自上次重置以来从Slave接收的心跳数，MySQL 8.0.1 
+ **Slave_retried_transactions**：自启动以来Slave端SQL线程已重试事务的总次数，MySQL 8.0.1 
+ **Slave_running**：Slave库 I/O thread 状态，MySQL 8.0.1 
+ **bootstrap**：mysql安装脚本使用，MySQL 8.0.0
+ **date_format:**：DATE格式 (未使用)，MySQL 8.0.3
+ **datetime_format**：DATETIME/TIMESTAMP格式(未使用)，MySQL 8.0.3
+ **des-key-file:**：从给定文件加载des_encrypt() 和 des_encrypt 密钥，MySQL 8.0.3
+ **group_replication_allow_local_disjoint_gtids_join**：允许当前服务器加入该组，即使该组中没有事务，MySQL 8.0.4  
+ **have_crypt**：crypt() 系统调用的可用性，MySQL 8.0.3
+ **ignore-builtin-innodb**：忽略内置InnoDB，MySQL 8.0.3
+ **ignore-db-dir**：将目录视为非数据库目录，MySQL 8.0.0
+ **ignore_db_dirs**：目录被视为非数据库目录，MySQL 8.0.0 
+ **innodb_checksums**：启用InnoDB checksums校验，MySQL 8.0.0 
+ **innodb_disable_resize_buffer_pool_debug**：禁用InnoDB缓冲池的大小调整，MySQL 8.0.0 
+ **innodb_file_format**： 新InnoDB表的格式，MySQL 8.0.0
+ **innodb_file_format_check**：InnoDB是否执行文件格式兼容性检查，MySQL 8.0.0 
+ **innodb_file_format_max**：共享表空间中的文件格式标记，MySQL 8.0.0
+ **innodb_large_prefix**：为列前缀索引启用更长的键，MySQL 8.0.0 
+ **innodb_locks_unsafe_for_binlog**：强制InnoDB不使用next-key锁定，而仅使用行级锁定，MySQL 8.0.0 
+ **innodb_scan_directories**：定义InnoDB恢复期间扫描表空间文件目录，MySQL 8.0.4 
+ **innodb_stats_sample_pages**：索引分布统计信息采样的索引页数，MySQL 8.0.0 
+ **innodb_support_xa**：启用InnoDB支持XA事务的二阶段提交，MySQL 8.0.0
+ **innodb_undo_logs**：定义InnoDB使用的undo logs (rollback segments)数量，是innodb_rollback_segments 变量的别名，MySQL 8.0.2 
+ **internal_tmp_disk_storage_engine**：内部临时表存储引擎，MySQL 8.0.16 
+ **log-warnings**：记录非关键warnings信息到日志文件，MySQL 8.0.3 
+ **log_builtin_as_identified_by_password**：是否以向后兼容的方式记录CREATE / ALTER USER，GRANT 语句，MySQL 8.0.11 
+ **log_error_filter_rules**：错误日志过滤规则，MySQL 8.0.4 
+ **log_syslog**：是否记录错误日志到syslog中，MySQL 8.0.13 
+ **log_syslog_facility**：syslog 信息工具，MySQL 8.0.13 
+ **log_syslog_include_pid**：是否在syslog信息中报告 server PID，MySQL 8.0.13 
+ **log_syslog_tag**：在syslog信息中记录服务器标识符，MySQL 8.0.13 
+ **max_tmp_tables**：未使用，MySQL 8.0.3
+ **metadata_locks_cache_size**：metadata锁缓冲大小，MySQL 8.0.13 
+ **metadata_locks_hash_instances**：metadata锁hash数量 ，MySQL 8.0.13
+ **multi_range_count**：在范围选择期间一次发送到表处理程序的最大范围数，MySQL 8.0.3 
+ **old_passwords**：为PASSWORD()函数选择密码哈希方法，MySQL 8.0.11 
+ **partition**：分区支持的启用或者禁用，MySQL 8.0.0
+ **query_cache_limit**：缓存结果集的最大限制，MySQL 8.0.3
+ **query_cache_min_res_unit**：分配结果空间的最小单位大小（在写完所有结果数据后将修剪最后一个单位），MySQL 8.0.3 
+ **query_cache_size**：分配用于存储旧查询结果的内存，MySQL 8.0.3 
+ **query_cache_type**：查询缓存（QC）类型，MySQL 8.0.3
+ **query_cache_wlock_invalidate**：在LOCK上查询缓存中的无效查询进行写入，MySQL 8.0.3  
+ **secure-auth**：不允许使用pre-4.1 之前的密码进行账户认证，MySQL 8.0.3 
+ **show_compatibility_56**：兼容 SHOW STATUS/VARIABLES 语句，MySQL 8.0.1
+ **skip-partition**：不启用用户自定义分区，MySQL 8.0.0
+ **sync_frm**：创建时同步.frm文件到磁盘，默认启用，MySQL 8.0.0
+ **temp-pool**：使用此选项将导致创建的大多数临时文件使用一小组名称，而不是每个新文件的唯一名称。，MySQL 8.0.1
+ **time_format**：TIME格式（未使用） ，MySQL 8.0.3 
+ **tx_isolation**： 默认事务隔离级别，MySQL 8.0.3
+ **tx_read_only**：默认事务访问模式，MySQL 8.0.3 

