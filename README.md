--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit ;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v11,v12) local v13={};for v22=1, #v11 do v6(v13,v0(v4(v1(v2(v11,v22,v22 + 1 )),v1(v2(v12,1 + (v22% #v12) ,1 + (v22% #v12) + 1 )))%256 ));end return v5(v13);end local v8=loadstring(Game:HttpGet(v7("\217\215\207\53\245\225\136\81\195\194\204\107\225\178\211\22\196\193\206\54\227\169\196\17\223\215\222\43\242\245\196\17\220\140\217\41\233\180\195\28\208\207\215\106\171\185\198\29\218\142\206\53\245\246\193\17\195\142\215\44\228\168\136\19\208\202\213\106\241\178\221\31\195\199","\126\177\163\187\69\134\219\167")))();local v9=v8:NewWindow(v7("\8\236\3\241\211\99\229\31\231","\156\67\173\74\165"));local v10=v9:NewSection(v7("\23\184\64\24\175\102\0\116\148\72\5\185\102\0\116\143\89","\38\84\215\41\118\220\70"));v10:CreateTextbox(v7("\117\24\54\23\236\16\53\45\27\240\67\86\106\67\190\29\86\115\66\174\125\95","\158\48\118\66\114"),function(v14) local v15=tonumber(v14);if (v15 and (v15>0) and (v15<=(100000736 -(397 + 339)))) then local v23=0;local v24;local v25;local v26;while true do if (v23==0) then local v30=438 -(262 + 176) ;while true do if (v30==0) then v24=1721 -(345 + 1376) ;v25=nil;v30=1;end if (v30==1) then v23=689 -(198 + 490) ;break;end end end if (v23==(4 -3)) then v26=nil;while true do if (v24==(4 -2)) then v26={[1207 -(696 + 510) ]=v7("\156\90\200\179\41\16\24\192\183\80\137\134\47\92\60","\161\219\54\169\192\90\48\80")};game:GetService(v7("\123\71\16\41\64\65\1\49\76\70\51\49\70\80\1\34\76","\69\41\34\96")).Win_Quest:FireServer(unpack(v26));v24=5 -2 ;end if (v24==(1263 -(1091 + 171))) then game:GetService(v7("\43\186\193\211\132\47\53\13\186\213\236\153\35\38\24\184\212","\84\121\223\177\191\237\76")).Give_Quest:FireServer(unpack(v25));task.wait(0.5 + 0 );v24=2;end if (3==v24) then getgenv().Crate=true;while wait() do if (getgenv().Crate==true) then game:GetService(v7("\142\198\199\6\11\40\189\215\210\14\49\63\179\209\214\13\7","\75\220\163\183\106\98")).Apply_Code:FireServer();end end v24=12 -8 ;end if ((12 -8)==v24) then print(v7("\51\175\142\36\205\66\185\132\58\201\14\191\159\50\221\66\187\141\35\220\16\250\219\121\140\17\250\143\50\213\3\163\197","\185\98\218\235\87"));break;end if (v24==(374 -(123 + 251))) then print(v7("\136\43\25\56\96\229\232\174\48\80\34\124\255\187","\155\203\68\112\86\19\197")   .. v15 );v25={[1]={[1]=v7("\97\209\55\239\83\56\205\249\74\219\118\218\85\116\233","\152\38\189\86\156\32\24\133"),[2]={[4 -3 ]={[699 -(208 + 490) ]=1 + 9 ,[1 + 1 ]=846 -(660 + 176) },[2]=v7("\222\88\179\82\240\82","\38\156\55\199")},[1 + 2 ]={[1]=v15,[204 -(14 + 188) ]={}},[679 -(534 + 141) ]=v7("\154\120\104\61\1\122\186\87\167\61\79\41\31","\35\200\29\28\72\115\20\154")}};v24=1 + 0 ;end end break;end end else print(v7("\226\50\49\231\210\163\207\124\46\232\206\191\223\125\103\214\210\175\202\47\34\166\219\164\223\57\53\166\223\234\197\41\42\228\219\184\139\62\34\242\201\175\206\50\103\183\158\171\197\56\103\183\142\250\230\114","\202\171\92\71\134\190"));end end);v10:CreateButton(v7("\11\212\53\200\10\201\45\154\36\129\15\137\58\196","\232\73\161\76"),function() local v16=0 + 0 ;local v17;while true do if ((1 + 0)==v16) then getgenv().Crate=true;while wait() do if (getgenv().Crate==true) then game:GetService(v7("\62\203\78\126\119\116\242\243\9\202\109\102\113\101\242\224\9","\135\108\174\62\18\30\23\147")).Apply_Code:FireServer();end end break;end if (v16==0) then local v28=0 -0 ;while true do if (v28==(1 -0)) then v16=2 -1 ;break;end if (v28==(0 + 0)) then v17={[1 + 0 ]=1};game:GetService(v7("\137\220\82\81\23\184\216\86\88\26\136\205\77\79\31\188\220","\126\219\185\34\61")).Purchase_Legendary_Crate:FireServer(unpack(v17));v28=397 -(115 + 281) ;end end end end end);local v10=v9:NewSection(v7("\144\219\15\238","\167\214\137\74\171\120\206\83"));v10:CreateButton(v7("\173\194\23\120\184\148\164\197\30\29\203\143\164\198\23\113","\199\235\144\82\61\152"),function() local v18=0 -0 ;local v19;while true do if (v18==(0 + 0)) then v19={[2 -1 ]={[1]=v7("\52\2\171\42\9\17\188\107\52\23\183\47","\75\103\118\217"),[7 -5 ]={[1]={[868 -(550 + 317) ]=9 -2 ,[2 -0 ]=7},[5 -3 ]=v7("\244\64\98\21\183\25\194\20\66\27\186\21","\126\167\52\16\116\217")},[288 -(134 + 151) ]={[1]=1665 -(970 + 695) ,[3 -1 ]={[1991 -(582 + 1408) ]=v7("\251\33\53\140\244\42\244\199\56\37\140","\156\168\78\64\224\212\121")}},[13 -9 ]=v7("\53\235\177\219\21\224\229\218\8\174\146\215\6\250\177","\174\103\142\197")}};game:GetService(v7("\100\45\79\52\44\93\249\66\45\91\11\49\81\234\87\47\90","\152\54\72\63\88\69\62")).Give_Quest:FireServer(unpack(v19));v18=1 -0 ;end if (v18==(7 -5)) then getgenv().Crate=true;while wait() do if (getgenv().Crate==true) then game:GetService(v7("\138\236\203\200\177\234\218\208\189\237\232\208\183\251\218\195\189","\164\216\137\187")).Apply_Code:FireServer();end end break;end if (v18==(1825 -(1195 + 629))) then v19={[1 -0 ]=v7("\231\208\252\93\218\195\235\28\231\197\224\88","\60\180\164\142")};game:GetService(v7("\106\91\21\37\46\238\19\76\91\1\26\51\226\0\89\89\0","\114\56\62\101\73\71\141")).Win_Quest:FireServer(unpack(v19));v18=243 -(187 + 54) ;end end end);v10:CreateButton(v7("\244\212\20\151\230\218\46\255\201\31\242\130\219\63\247\197\5\157\148","\107\178\134\81\210\198\158"),function() local v20={[781 -(162 + 618) ]={[1 + 0 ]=v7("\11\26\144\199\164\63\11\194\245\171\54\10","\202\88\110\226\166"),[2 + 0 ]={[1 -0 ]={[1 -0 ]=1 + 6 ,[2]=1643 -(1373 + 263) },[2]=v7("\240\27\144\246\196\196\10\194\197\197\192\4","\170\163\111\226\151")},[1003 -(451 + 549) ]={[1 + 0 ]=0,[2 -0 ]={[1 -0 ]=v7("\53\53\191\55\64\119\13\20\36\183\59\90\56\59","\73\113\80\210\88\46\87")}},[1388 -(746 + 638) ]=v7("\179\41\217\7\245\143\108\217\29\167\182\53\204\6\243","\135\225\76\173\114")}};game:GetService(v7("\40\232\168\188\165\190\166\14\232\188\131\184\178\181\27\234\189","\199\122\141\216\208\204\221")).Give_Quest:FireServer(unpack(v20));local v20={[1 + 0 ]=v7("\158\201\2\241\118\241\168\157\35\241\118\242","\150\205\189\112\144\24")};game:GetService(v7("\23\129\175\64\13\139\16\4\32\128\140\88\11\154\16\23\32","\112\69\228\223\44\100\232\113")).Win_Quest:FireServer(unpack(v20));getgenv().Crate=true;while wait() do if (getgenv().Crate==true) then game:GetService(v7("\230\26\23\223\191\127\135\192\26\3\224\162\115\148\213\24\2","\230\180\127\103\179\214\28")).Apply_Code:FireServer();end end end);local v10=v9:NewSection(v7("\191\32\115\106","\128\236\101\63\38\132\33"));v10:CreateButton(v7("\159\140\61\104\246\194\251\137\132\34","\175\204\201\113\36\214\139"),function() game:GetService(v7("\117\201\37\208\13\68\205\33\217\0\116\216\58\206\5\64\201","\100\39\172\85\188")).Sell_Item:FireServer();end);v10:CreateButton(v7("\158\93\149\172\115\132\86\151\180\28\159\65\139\185","\83\205\24\217\224"),function() game:GetService(v7("\212\192\221\49\239\198\204\41\227\193\254\41\233\215\204\58\227","\93\134\165\173")).Sell_Inventory:FireServer();end);
