<br/>
<img align="left" src="./assests/wiki-correct.svg" width="110" height="110" alt=""/>
<p align="center">
    <font size="6">MCBE Protocol Wiki Road Map</font>
</p>

----
<br/>
<br/>

This is a road map of what goals this project has, and how we plan on achieving them. We do have a [Project](https://github.com/orgs/Bedrock-OSS/projects/7) page that will have better notes and more up-to-date stuff.

## The Plan

The plan for this site is to provide info on all of Minecraft Bedrock Protcols (Bedrock, RakNet, NetherNet). Currently docs on all of these are everywhere, out of date, or just hard to read/understand. We want to bring all of these docs into one place, keep it up-to-date, and make it as easy as possible to understand.

We want to make it fairly similar to the current bedrock wiki, design wise, but use a different SSG(Static Site Generator) as we have had problems with Vitepress.

For keeping the protocols (mostly bedrock) up-to-date, we are gonna use the offical docs from Mojang. The only issue with this is that it has a fair amount of errors, but this shouldn't be too hard to add fixes to.

Currently we haven't thought of a good way to document multiple version protocols so as of now we are only doing the most up-to-date version.

For the actual layout of the protocol docs, we are gonna have it so the website will generate all the packet/enum/type pages with a table on the layout/data. That will be the base page. If we wish to add notes onto a packet/enum/type we add a md file, named accordingly, and it will add the table/data when generated. It will be customizable so you can add notes either before or after it, or both.

## Goals

| Goal                      | Achieved | Notes                                                                                |
|---------------------------|----------|--------------------------------------------------------------------------------------|
| Pick a SSG                | ➖       | Vitepress is simple & small but has problems                                         |
| Transfer Docs             | ✖️       | Should be able to split the old docs up into new pages                               |
| Transfer/Make Site Design | ✖️       | Stil TBD, makes sense to keep the same design                                        |
| Protocol Parser           | ➖       | Already been started but not completely finished and needs features                  |
| Protocol Doc Generator    | ✖️       | Should be pretty simple to convert the proto file to a table and append our notes it |