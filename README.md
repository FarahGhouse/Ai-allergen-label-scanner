# AI Allergen Label Scanner

SDG Alignment: SDG 3 (primary), SDG 10 (secondary)

# Problem 

**Who Is Affected:**
Harold is a fictional 64-year-old San Jose resident with age-related vision changes. He is buying a cake at the grocery store for his family as a gift. His grandchild and daughter are allergic to peanuts.

Harold tries to read the ingredients list on the label but cannot because the text is too small and crowded. He does not have much time to shop and cannot find a store employee to help.

**What Breaks Down Today?**
The allergen information Harold needs is printed on the label, but he cannot read it at the moment. Without this information, he must either guess and risk a serious allergic reaction for someone he loves or leave the store without the gift.

Labels may also use technical or indirect wording, such as “may contain traces of peanuts,” or ingredient names that do not directly say “peanut.” This makes allergens easy to miss, even for people with good eyesight.

Existing options, such as magnifiers or phone zoom features, may not be enough. They help users enlarge the text but still require them to find and interpret allergen terms on their own.

Barcode-scanning apps may also be unreliable because their databases may not include bakery items or may contain outdated information. Asking a store employee depends on someone being available and knowing the product’s ingredients.

As a result, people who are most exposed to the risk—such as family members with food allergies—may depend on a shopper who cannot read the label.

**Why Not Use Something Simpler?**
A camera zoom feature or magnifier can help with reading but does not interpret allergen terms.

Barcode-scanning apps depend on databases that may be outdated or may not include the product. Asking store employees depends on staff availability and their knowledge of the ingredients.

Our prototype reads the label directly from the product in the person’s hand. It also answers questions about the label in plain language.

 **Scope and Limitations:**
This is a prototype that uses synthetic or non-identifying label photos. It reports what is written on the label, and users can ask questions such as:

> Is milk a listed ingredient?

The prototype will never declare that a product is completely “safe.” Users should always verify allergen information with the product packaging or a qualified professional.

# AI Capability 

**Capabilities used:** 
Lab 3 (image recognition) and Lab 2 (structured data extraction)
