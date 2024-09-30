# General Messages
general:
  nametag:
    prefix: '&8[&9UltimateKits&8]'
  type:
    command: '&7Command'
    chance: Chance
    category: Category
    money: '&6Money'
    link: '&9Link'
    free: Free
    any: Any

# Interface Messages
interface:
  selector:
    kit: '&c%kit%'
    title: '&8Server kits'
    details: '&7Hello &e%player%&7!|&7Listed below are our server''s kits.||&7Click on the &eicon &7representing the &ekit |&7inorder to &epreview, claim or buy &7it.'
    aboutkitprice: '&7This kit costs &a$%price%&7.'
    aboutkit: '&7Can''t open a kit?|&7Rank up to gain access!'
    leftpreview: '&6&lLEFT CLICK &7to preview kit.'
    rightclaim: '&6&lRIGHT CLICK &7to claim kit.'
    rightbuy: '&6&lRIGHT CLICK &7to buy kit.'
    adminlore: '&6Middle Click &7to edit positioning.'
    editlore: '&6&lEdit Mode||&6Left Click &7to move kit left|&6Right Click &7to move kit right||&6Middle Click &7to go back.'
  categoryselector:
    title: '&8Server Kit Categories'
    details: '&7Hello &e%player%&7!|&7Listed below are our server''s kits.||&7Click on a &ecategory &7to view |&7the contained kits.'
    view: '&6&lCLICK &7to view category.'
  hologram:
    previewonly: Click to Preview!
    preview: Right-Click to Preview!
    buylink: Left-Click for Buy Link!
    buyeco: Left-Click to buy for &a$%price%&f!
    crate: Left-Click with a key to open!
    daily: Left-Click to Claim!
  button:
    buynow: '&aBuy Now'
    back: '&9Back'
    exit: '&cExit'
    next: '&7Next Page'
    last: '&7Last Page'
    clickeco: '&7Click to buy for &a%price%&7.'
    edit: '&6Edit'
  preview:
    title: '&9Previewing kit: &8%kit%'
  yesno:
    title: '&9Buy for &a$%price%&9?'
    'yes': '&a&lYes'
    'no': '&c&lNo'
  key:
    title: '&5%kit% &fKit Key'
    name: '&e%name% &fKey'
    description1: '&fRight-Click on [a ]&c&l%kit%&f kit'
    description2: '&fand receive its contents!'
    description3: '&fand receive some of its contents!'
    description4: '&fGives kit &c&l%amt% &ftimes.'
  crate:
    title: '&5%kit% &f%crate% Crate'
    description1: '&fRight-Click to open'
    description2: '&fand receive its contents!'
    description3: '&fand receive some of its contents!'
    description4: '&fLeft-Click to preview'

  # Administrative interfaces
  kitblock:
    title: '&8This contains &a%kit%'
    switchtype: '&5&lSwitch kit type'
    switchtypelore: '&7Click to swap this kit blocks function.|Preview|Crate|Claim'
    decor: '&9&lDecor Options'
    decorlore: '&7Click to edit the decoration|&7options for this kit.'
    edit: '&a&lEdit kit'
    editlore: '&7Click to edit the kit|&7contained in this block.'
  kitdecor:
    title: '&8Editing decor for &a%kit%&8.'
    hologram: '&9&lToggle Holograms'
    particle: '&9&lToggle Particles'
    display: '&9&lToggle DisplayItems'
    displayone: '&9&lToggle DisplayItem Override'
    displayonelore: '%enabled%||&7Enabling this option will|&7override the DisplayItems|&7above your kit to the single|&7DisplayItem set in this kit|&7GUI options.'
    settingon: '&7Currently: &aEnabled&7.'
    settingoff: '&7Currently &cDisabled&7.'
  kitsell:
    title: '&8Selling Options for &a%kit%&8.'
    nosell: '&c&lSet not for sale'
    nosellon: '&7Currently &aFor Sale&7.'
    noselloff: '&7Currently &cNot For Sale&7.'
    noselllore: '%onoff%||&7Clicking this option will|&7remove this kit from sale.'
    link: '&a&lSet kit link'
    linkon: '&7Currently: &a%kit%&7.'
    linkoff: '&7Currently: &cNot set&7.'
    linklore: '%onoff%||&7Clicking this option will|&7allow you to set a link|&7that players will receive|&7when attempting to purchase|&7this kit.'
    linkprompt: 'Kit to link:'
    linknoeco: '&8ECO has been removed from this kit. Note you cannot have ECO & LINK set at the same time..'
    price: '&a&lSet kit price'
    priceon: '&7Currently: &a$%price%&7.'
    priceoff: '&7Currently: &cNot set&7.'
    pricelore: '%onoff%||&7Clicking this option will|&7allow you to set a price|&7that players will be able to|&7purchase this kit for|&7requires a compatible economy plugin&7.'
    pricenoeco: '&8You must have an economy plugin installed to utilize economy..'
    priceprompt: 'Set Price:'
    pricenonumber: '&a%input% &8is not a positive number.'
    pricenolink: '&8LINK has been removed from this kit. Note you cannot have ECO & LINK set at the same time..'
  kitguioptions:
    title: '&8GUI Options for &a%kit%&8.'
    holo: '&9&lSet Title'
    holoon: '&7Currently: &a%title%&7.'
    holooff: '&7Currently: &cNot set&7.'
    hololore: '%onoff%||&7Left-Click: &9to set|&9the kit title for holograms|&9and the kit / kit selector GUIs.||&7Right-Click: &9to reset.'
    holoprompt: 'Set Title:'
    holoset: '&8Title &5%title%&8 added to Kit &a%kit%&8.'
    item: '&9&lSet DisplayItem'
    itemon: '&7Currently set to: &a%item%&7.'
    itemoff: '&7Currently &cDisabled&7.'
    itemlore: '%onoff%||&7Left-Click to: &9Set a|&9display item for this kit|&9to the item in your hand.||&7Right-Click to: &9Remove the item.'
    itemnoitem: '&8You must be holding an item to use this function.'
    itemset: '&8Custom Item Display set for kit &a%item%&8.'
    itemremoved: '&8Custom Item Display removed from kit &a%kit%&8.'
    hide: '&9&lHide kit'
    hideon: '&7Currently: &cHidden&7.'
    hideoff: '&7Currently: &aVisible&7.'
    hidelore: '%onoff%||&7A hidden kit will not|&7show up in the /kit gui.|&7This is usually optimal for|&7preventing players from seeing|&7non obtainable kit or starter kit.'
  kitoptions:
    title: '&8General Options for &a%kit%&8.'
    delay: '&9&lChange Delay'
    delaylore: '&7Currently set to: &a%delay%&7.||&7Use this to alter this kit delay.||&7Use &6-1 &7to make this kit single|&7use only.'
    delayprompt: 'Delay in Seconds:'
    delaynonumber: '&a%input% &8is not a number.'
    category: '&5&lSet Category'
    categorylore: '&7Currently set to: &a%category%&7.||&7Adding this kit to a category will|&7cause it do be displayed in|&7that category.||&cRight click to remove.'
    categoryprompt: 'Category name:'
    notacategory: '&cThat is not a category...'
    destroy: '&c&lDestroy Kit'
    destroylore: '|&7Click this to destroy this kit.'
    destroyprompt: Enter "%kit%"
    destroyok: '&cKit destroyed successfully.'
    destroycancel: '&cKit was not Destroyed.'
  kiteditor:
    title: '&8You are editing kit: &9%name%&8.'
    info: '&5&l%kit%|&fPermissions:|&7%perm%'
    generaloptions: '&6General Options'
    generaloptionslore: '&7Click to edit adjust|&7general options.'
    sellingoptions: '&9Selling Options'
    sellingoptionslore: '&7Click to edit adjust|&7selling options.'
    guioptions: '&5GUI Options'
    guioptionslore: '&7Click to edit GUI options|&7for this kit.'
    addcommand: '&fAdd Command'
    addcommandlore: '&7Click to add a command|&7to this kit.'
    addcommandprompt: Enter Command (No /)
    addcommandok: '&8Command &5%command%&8 has been added to your kit.'
    addeconomy: '&6Add Economy'
    addeconomylore: '&7Click to add money|&7to this kit.'
    addeconomyprompt: Enter Price (No $)
    addeconomyok: '&8Money &5$%amount%&8 has been added to your kit.'
    animation: '&6Kit Animation'
    animationlore: '&7Currently: &6%animation%'
    clone: '&aClone Kit'
    clonelore: '&7Use this to create an identical|&7kit with a different name.'
    itemediting: '&6Switch To Item Editing'
    itemeditinglore: '&7Click to enable|&7item editing.'
    itemmoving: '&6Switch To Item Moving'
    itemmovinglore: '&7Click to switch back|&7to item moving.'
    switchtoinventory: '&6Switch To Your Inventory'
    switchtoinventorylore: '&7Click to switch to|&7your inventory.'
    switchtokitfunctions: '&6Switch To Kit Functions'
    switchtokitfunctionslore: '&7Click to switch back|&7to the kit functions.'
    itemfunctionlore: '&7Display Item: &6%item%|&7Display Name: &6%name%|&7Display Lore: &6%lore%||&7Left-Click: &6To set a display item.|&7Middle-Click: &6To set a display name.|&7Right-Click: &6To set display lore.|&7Shift-Click: &6To set chance.||&7Display options only show up on display.|&7This can be useful if you want to explain|&7What an item does without putting it in the|&7permanent lore.||&6Leave function mode to move items.'
    saved: '&8Changes to &a%kit% &8saved successfully.'

# Command Messages
command:
  general:
    noperms: '&cYou do not have permission to do that!'
  kit:
    nokitsupplied: '&7Please include a kit to preview.'
    kitdoesntexist: '&cThat kit does not exist.'
    nokitatblock: '&8This block does not contain a kit.'
    kitalreadyexists: '&cThat kit already exists.'
    playernotfound: '&cThis player is not online or doesn''t exist.'
  crate:
    given: '&9Gave &7%player% &9crate &7%crate% &9for kit &7%kit%.'
    doesntexist: '&cThis crate is not loaded.'

# Event Messages
event:
  preview:
    kit: '&9You are now previewing kit &7%kit%&9.'
  crate:
    notyet: '&cYou need to wait &4%time% &cbefore you can use this.'
    wrongkey: '&cThis key doesn''t belong to this kit..'
    success: '&9Successfully opened a crate.'
    given: '&9You have received a %crate% %kit% crate.'
    needkey: '&cYou need the right key to get this kit'
  claim:
    cannotafford: '&9You cannot afford to buy kit &7%kit%&9.'
    nottwice: '&9You can only receive this kit once.'
    purchasesuccess: '&9You have purchased kit &7%kit%&9.'
    givesuccess: '&9You have received kit &7%kit%&9.'
    delay: '&cYou need to wait &4%time% &cbefore you can use this.'
    eco: '&7You received &a%amt%&7.'
    once: '&7Cooldown: &6You already claimed this kit!'
    ready: '&7Cooldown: &6Ready for use!'
    wait: '&7Cooldown: &6%time%'
    noaccess: '&7Cooldown: &cNo Access..'
    full: '&cYour inventory is too full to claim this kit!'
  create:
    won: '&7You got a &6%item%&7.'
  purchase:
    cancelled: '&cPurchase Canceled.'
  key:
    given: '&9You have received a &a%kit% &9kit key.'
    success: '&9You have successfully redeemed a key for the kit &7%kit%&9.'
