# Steam Description

```
Adds policies to control how the "The Flesh is Weak" and "Synthetic Evolution" ascension perks get applied to pops. Finishing either special project will have a different effect depending on the active associated policy.

[h2]Policies[/h2]
[list]
  [*]Cybernetic Enhancement for The Flesh is Weak
  [*]Synthetic Enhancement for Synthetic Evolution
[/list]

[h2]Options[/h2]
[table]
  [tr]
    [th]Option[/th]
    [th]Effect[/th]
  [/tr]
  [tr]
    [td]Optional  [/td]
    [td]Most eligible pops are upgraded but some may choose not to.[/td]
  [/tr]
  [tr]
    [td]Discretionary  [/td]
    [td]No pops will be upgraded - changes to pops are made exclusively by assimilation.[/td]
  [/tr]
  [tr]
    [td]Compulsory  [/td]
    [td]All eligible pops are upgraded. This is the same behavior as vanilla.[/td]
  [/tr]
[/table]

[h2]Compatibility[/h2]

Not compatible with mods that change The Flesh is Weak or Synthetic Evolution ascension perks or associated effects.

[b]Overwrites[/b]
[list]
  [*]ap_the_flesh_is_weak
  [*]ap_synthetic_evolution
[/list]
```

# Overwrites & Replacements

## Items

common/ascension_perks/00_ascension_perks.txt
- ap_the_flesh_is_weak
- ap_synthetic_evolution

## Special Projects

common/special_projects/00_projects_utopia.txt
- FLESH_IS_WEAK_PROJECT
- SYNTHETIC_EVOLUTION_PROJECT

## Events

events/utopia_on_action_events.txt
- utopia.2500
- utopia.2501
- utopia.2550
- utopia.2551