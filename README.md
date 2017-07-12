var Bot = require('dragon-bot'); var bot = new Bot({    email: <Tia.Schioppo@bayridgeprep.org>,    password: <Tia Tia Tia>}); 
.on(bot.triggers.command, 'speak')    .do(function( args ){ this.reply('roar');});
.on(bot.triggers.command, 'rollover')    .do(function( args ){ this.reply('dragon flips itself on its back at your feet');});
.on(bot.triggers.command, 'fire attack')    .do(function( args ){ this.reply('dragon breaths fire at intruder ');});
.on(bot.triggers.command, ' bro fist')    .do(function( args ){ this.reply('dragon puts one of his front feet to your fist');});   
.on(bot.triggers.command, ' sit')    .do(function( args ){ this.reply('dragon sits down right in front of you');});    
.on(bot.triggers.command, 'lay down')    .do(function( args ){ this.reply('dragon plops down in front of you');});bot.connect();
.on (bot . trigger .react, / I'm back/)    .do(function(args) { /* <- dragon comes out to greet you*/        console.log(args.message);
.on (bot . trigger .react, / feed /)    .do(function(args) { /* <- dragon nibbles the food from your hand*/        console.log(args.message);
.on (bot . trigger .react, / Pet /)    .do(function(args) { /* <- dragon rubs up against you and roars happily */        console.log(args.message);
.on (bot . trigger .react, / ride /)    .do(function(args) { /* <- you and your dragon soar through the clouds*/        console.log(args.message);
.on (bot . trigger .react, / bath time /)    .do(function(args) { /* <- dragon looks for a place to hide*/        console.log(args.message);
.on (bot . trigger .react, / scale shining/)    .do(function(args) { /* <- dragon scales glimmer in the light*/        console.log(args.message); 
bot.addService(name,service)
bot.getSerice(name)
bot.addService('help',
bot.service.help;
add(https://www.google.com/?gws_rd=ssl)
