<!-- 7.3.2 START AUTO GENERATED -->

# 7.3.2 (2020-11-11)

  ### Features / Enhancements
  * **CloudWatch Logs**: Change how we measure query progress. [#28912](https://github.com/grafana/grafana/pull/28912), [@aocenas](https://github.com/aocenas)
  * **Dashboards / Folders**: delete related data (permissions, stars, tags, versions, annotations) when deleting a dashboard or a folder. [#28826](https://github.com/grafana/grafana/pull/28826), [@AgnesToulet](https://github.com/AgnesToulet)
  * **Gauge**: Improve font size auto sizing. [#28797](https://github.com/grafana/grafana/pull/28797), [@torkelo](https://github.com/torkelo)
  * **Short URL**: Cleanup unvisited/stale short URLs. [#28867](https://github.com/grafana/grafana/pull/28867), [@wbrowne](https://github.com/wbrowne)
  * **Templating**: Custom variable edit UI, change options input into textarea. [#28322](https://github.com/grafana/grafana/pull/28322), [@darrylsepeda](https://github.com/darrylsepeda)

  ### Bug Fixes
  * **Cloudwatch**: Fix issue with field calculation transform not working properly with Cloudwatch data. [#28761](https://github.com/grafana/grafana/pull/28761), [@torkelo](https://github.com/torkelo)
  * **Dashboard**: fix view panel mode for Safari / iOS. [#28702](https://github.com/grafana/grafana/pull/28702), [@jackw](https://github.com/jackw)
  * **Elasticsearch**: Exclude pipeline aggregations from order by options. [#28620](https://github.com/grafana/grafana/pull/28620), [@simianhacker](https://github.com/simianhacker)
  * **Panel inspect**: Interpolate variables in panel inspect title. [#28779](https://github.com/grafana/grafana/pull/28779), [@dprokop](https://github.com/dprokop)
  * **Prometheus**: Fix copy paste behaving as cut and paste. [#28622](https://github.com/grafana/grafana/pull/28622), [@aocenas](https://github.com/aocenas)
  * **StatPanels**: Fixes auto min max when latest value is zero. [#28982](https://github.com/grafana/grafana/pull/28982), [@torkelo](https://github.com/torkelo)
  * **TableFilters**: Fixes filtering with field overrides. [#28690](https://github.com/grafana/grafana/pull/28690), [@hugohaggmark](https://github.com/hugohaggmark)
  * **Templating**: Speeds up certain variable queries for Postgres MySql MSSql. [#28686](https://github.com/grafana/grafana/pull/28686), [@hugohaggmark](https://github.com/hugohaggmark)
  * **Units**: added support to handle negative fractional numbers. [#28849](https://github.com/grafana/grafana/pull/28849), [@mckn](https://github.com/mckn)
  * **Variables**: Fix backward compatibility in custom variable options that contain colon. [#28896](https://github.com/grafana/grafana/pull/28896), [@mckn](https://github.com/mckn)

<!-- 7.3.2 END AUTO GENERATED -->

<!-- 7.3.1 START AUTO GENERATED -->

# 7.3.1 (2020-10-30)

  ### Bug Fixes
  * **Cloudwatch**: Fix duplicate metric data. [#28642](https://github.com/grafana/grafana/pull/28642), [@zoltanbedi](https://github.com/zoltanbedi)
  * **Loki**: Fix error when some queries return zero results. [#28645](https://github.com/grafana/grafana/pull/28645), [@ivanahuckova](https://github.com/ivanahuckova)
  * **PanelMenu**: Fix panel submenu not being accessible for panels close to the right edge of the screen. [#28666](https://github.com/grafana/grafana/pull/28666), [@torkelo](https://github.com/torkelo)
  * **Plugins**: Fix descendent frontend plugin signature validation. [#28638](https://github.com/grafana/grafana/pull/28638), [@wbrowne](https://github.com/wbrowne)
  * **StatPanel**: Fix value being under graph and reduced likelihood for white and dark value text mixing. [#28641](https://github.com/grafana/grafana/pull/28641), [@torkelo](https://github.com/torkelo)
  * **TextPanel**: Fix problems where text panel would show old content. [#28643](https://github.com/grafana/grafana/pull/28643), [@torkelo](https://github.com/torkelo)

<!-- 7.3.1 END AUTO GENERATED -->