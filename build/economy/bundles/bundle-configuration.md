# ⚙️ Bundle Configuration

In order to begin configuring a bundle, you will need to navigate to the 'Economy' section under 'Build', click on 'Bundles', and then select the '**Create Bundle**' button to access the configuration settings.

***

### Bundle Information

1. **Bundle Icon**: Assign or update the graphic representation of your bundle.
2. **Display Name**: Assign your bundle's display name.
3. **Bundle ID**: Enter a unique identifier for your bundle.
4. **Bundle Description**: Give a brief explanation of your bundle's contents and use.

***

### Add Content to Bundle

Here, you can select items and currencies to include in your bundle. Add as many as you like and set the quantity for each content that you add.

***

### Pricing

1. **Pricing Options**: Similar to item pricing, this involves choosing a currency (Virtual, IAP, or Real Money Gaming Currency), setting the price amount, and optionally, adding a discount.

{% hint style="info" %}
When opting for Real Money Gaming (RMG) Currency, an extra field labeled 'Bonus Cash Allowance' appears. This field denotes the maximum amount of bonus cash (a component of your RMG Currency) that can be applied towards the bundle's purchase. If a player has the corresponding bonus cash, it will be automatically utilised during the transaction, up to the maximum limit.
{% endhint %}

For a more comprehensive understanding of the bonus cash mechanism and RMG Currency, please refer to the dedicated [Real Money Gaming](https://www.dirtcube.xyz) section.

{% hint style="info" %}
&#x20;Just like items, a combination of currencies can also be used to price a bundle.
{% endhint %}

You may want to check out:

{% content-ref url="../currencies/currency-types.md" %}
[currency-types.md](../currencies/currency-types.md)
{% endcontent-ref %}

***

### Access and Eligibility

1. **Lock By**: Determine if access to the bundle is restricted by another item/bundle or a progression system.
2. **Select Item/Bundle**: If the bundle is locked by another item/bundle, choose the specific item/bundle from the dropdown menu.
3. **Choose Progression System**: If the bundle is locked by a progression system, select the specific system from the dropdown menu.
4. **Set Progression System Level:** Define the level within the chosen progression system that a player must reach to unlock the bundle.
5. **Choose Segments**: Select the player segments for whom the bundle will be visible.

You may want to check out:

{% content-ref url="managing-bundle-access.md" %}
[managing-bundle-access.md](managing-bundle-access.md)
{% endcontent-ref %}

{% content-ref url="../../progression/progression-systems/" %}
[progression-systems](../../progression/progression-systems/)
{% endcontent-ref %}

***

### Bundle Types

1. **Bundle Type**: Specify whether the bundle is 'durable' (permanently available) or 'consumable' (used up over time or with use).
2. **Count/Time Usage**: If the bundle is consumable, choose whether it's depleted by count (number of uses) or time (duration).
3. **Bundle Subtypes**: Determine if the bundle is stackable, equippable, rentable, tradable, or time-stackable (if consumable by time).
4. **Max Stack Count**: If the bundle is stackable, specify the maximum number of bundles that can be stacked together.
5. **Limited Availability**: Indicate if the bundle is available in a limited quantity. If 'Limited' is selected, specify the quantity.
6. **Bundle Open**: Choose if the bundle opens 'Automatically' upon purchase or 'Manually' by the player. This is how you can create a container-like functionality if you select manually. If combined with the "lock by item/bundle" feature, you can create a container that requires a key to open. Please refer to the dedicated section for '[Containers](containers.md)' to learn more about this.

You may want to check out:

{% content-ref url="bundle-types.md" %}
[bundle-types.md](bundle-types.md)
{% endcontent-ref %}

{% content-ref url="containers.md" %}
[containers.md](containers.md)
{% endcontent-ref %}

***

### Custom Data

1. **Tags**: Use keywords to help categorise and manage your bundles more effectively.
2. **Meta Data**: Enter any additional attributes for the bundle, defined as key-value pairs, to enhance your bundle configuration.

***

Specter's robust and versatile bundle management system allows you to create and customise a wide variety of in-game bundles, catering to various gameplay styles and player preferences.
