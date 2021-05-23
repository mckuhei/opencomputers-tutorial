# 这是什么？

这是一个面向中国人的OpenComputers教程，OpenComputers简称OC

# 本教程使用的OC版本是什么？

本教程使用最新版的[MC1.12.2-1.7.5.217](https://ci.cil.li/job/OpenComputers-MC1.12/217/artifact/build/libs/OpenComputers-MC1.12.2-1.7.5.217.jar)

# 状态

[![auto-generate-gitbook](https://github.com/kebufu/opencomputers-tutorial/actions/workflows/build.yml/badge.svg)](https://github.com/kebufu/opencomputers-tutorial/actions/workflows/build.yml)

斜体表示未完成，粗体表示有待补充

- *第一章 初识OpenComputers*
  - [**制作一台电脑**](第一章%20初识OpenComputers/制作一台电脑.md)
  - [*打开它！*](第一章%20初识OpenComputers/打开它！.md)

<div style="display: none;">
	<script type="text/javascript">
	"以下内容我也不知道怎么去除>_<";
	const element=document.querySelector("#book-search-results > div.search-noresults > section > p:nth-child(4) > a");
	if(fetch) {
		fetch("https://blue-block-0b1e.mckuhei.workers.dev/job/OpenComputers-MC1.12/lastSuccessfulBuild/api/xml?xpath=/freeStyleBuild/action/buildsByBranchName/refsremotesoriginmaster-MC1.12/buildNumber").then(e => {if(e.status==200) return e.text()}).then(e => {
			if(e!=undefined) {
				const lastBuild=e.substr(13).substr(0,3);
				console.log("最后构建:"+lastBuild);
				element.innerText=element.innerText.substr(0,element.innerText.length-3)+lastBuild;
				element.href="https://ci.cil.li/job/OpenComputers-MC1.12/"+lastBuild+"/artifact/build/libs/OpenComputers-"+element.innerText+".jar";
			};
		});
	};
</script>  
</div>