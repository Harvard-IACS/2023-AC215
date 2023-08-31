---
layout: page
title: Schedule
description: Listing of course modules and topics.
nav_order: 1
---

# Schedule

Overall schedule

Certainly! Crafting a policy for usage of publicly available class material is important for ensuring that the resources you've created are utilized in the manner you intend. Below is a sample policy that you might include in your syllabus, class website, or as a disclaimer accompanying the publicly available material:

---

### Policy on Usage of Publicly Available Class Material

1. **Permitted Use**: Class Material is made available primarily for the educational benefit of enrolled students and may be used by others for personal educational purposes only.

2. **Prohibited Use**: 
    - Selling or commercializing any part of the Class Material.
    - Sharing, distributing, or publishing any part of the Class Material in any form or through any medium without explicit permission from the instructor.
    - Modifying or altering the Class Material to create derivative works.

3. **Attribution**: Any permitted use of the Class Material must carry appropriate acknowledgment of the source (e.g., the instructor's name, course title, and institution).

4. **Enforcement**: Failure to comply with this policy may result in legal action and/or disciplinary measures as applicable.

#### Consent:
By accessing and using the Class Material, you indicate your acknowledgment and acceptance of this policy.

---

Feel free to modify this sample policy to better align with your specific needs and institutional guidelines.

{% for module in site.modules %}
{{ module }}
{% endfor %}
