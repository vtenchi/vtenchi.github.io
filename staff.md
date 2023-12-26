---
layout: default
title: "Staff"
---
<div class="grid grid-cols-1 md:grid-cols-3 gap-4">
    {%- for entry in site.staff_members -%}
        {%- include staff_member.html item = entry -%}
    {%- endfor -%}
</div>
