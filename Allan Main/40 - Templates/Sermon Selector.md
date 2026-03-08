---
date: 2026-03-03
pastor:
status: 🔄 Processing
tags:
---

<%*
const folder = "20_Projects/EFC Quito/02_Sermon_Notes";
const options = ["Standard Sermon Note", "Raw Transcript"];
const templateFiles = ["Template - EFC Sermon Note", "Template - Raw Transcript"];

const choice = await tp.system.suggester(options, templateFiles);
if (choice) {
    await tp.file.include(`[[${choice}]]`);
}
%>