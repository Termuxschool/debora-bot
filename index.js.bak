const qrcode = require("qrcode-terminal");
const moment = require("moment");
const cheerio = require("cheerio");
const imageToBase64 = require('image-to-base64');
const get = require('got');
const fs = require("fs");
const dl = require("./lib/downloadImage.js");
const fetch = require('node-fetch');
const urlencode = require("urlencode");
const axios = require("axios");
const speed = require('performance-now');

//WM Deniambrose

const apivhtear = 'YOUR_APIKEY';
const apibarbar = 'YOYR_APIKEY';
const tobzkey = 'YOUR_APIKEY';
const BotName = 'DEBORA_BOT';
const wa = 'https://chat.whatsapp.com/FTi0dgUy4en4DNtM7G5Bse';
const ow = 'Luan_Pereira';
const eror = '[ERROR]';
const nomorowner = '085747852482';
const ovo = '085';
const pulsa = '0857-4785-2482';
const dana = '0857-4785-2482';
const gopay = '085';
const instagram = 'http://www.instagram.com/luan_pereira_2020_';
const aktif = 'Tergantung internet';
const vcard = 'BEGIN:VCARD\n'
  + 'VERSION:3.0\n' // MAU NGAPAIN NJIR
  + 'FN:Luan_Pereira\n' // NAMA KU JANGAN DIHAPUS
  + 'ORG:OWNER BOT;\n' // INI WM DABOT
  + 'TEL;type=CELL;type=VOICE;waid=6282347594640:+62 823-4759-4640\n' //GUE CAPE TOD
  + 'END:VCARD' //JANGAN DIHAPUS WM DABOT
//
const
  {
    WAConnection,
    MessageType,
    Presence,
    MessageOptions,
    Mimetype,
    WALocationMessage,
    WA_MESSAGE_STUB_TYPES,
    ReconnectMode,
    ProxyAgent,
    waChatKey,
    GroupSettingChange,
    mentionedJid,
    processTime,
  } = require("@adiwajshing/baileys");
var jam = moment().format("HH:mm");
//Deniambrose
function foreach(arr, func) {
  for (var i in arr) {
    func(i, arr[i]);
  }
}
const conn = new WAConnection()
conn.on('qr', qr => {
  qrcode.generate(qr,
    {
      small: true
    });
  console.log(`[ ${moment().format("HH:mm:ss")} ] SUBSCRIBE YT DENI AMBROSE & RAMLAN CHANEL`);
});

conn.on('credentials-updated', () => {
  // save credentials whenever updated
  console.log(`credentials updated$`)
  const authInfo = conn.base64EncodedAuthInfo() // get all the auth info we need to restore this session
  fs.writeFileSync('./Ramlan.json', JSON.stringify(authInfo, null, '\t')) // save this info to a file
})
fs.existsSync('./Ramlan.json') && conn.loadAuthInfo('./Ramlan.json')
// uncomment the following line to proxy the connection; some random proxy I got off of: https://proxyscrape.com/free-proxy-list
//conn.connectOptions.agent = ProxyAgent ('http://1.0.180.120:8080')
conn.connect();


conn.on('message-status-update', json => {
  const participant = json.participant ? ' (' + json.participant + ')' : '' // participant exists when the message is from a group
})
setInterval(function () {
  for (i = 0; i < 3; i++) {
    console.log(`[ ${moment().format("HH:mm:ss")} ] => Ola I'm Debora`)
  }
}, 15000)

//function

conn.on('message-new', async (m) => {
  const messageContent = m.message
  const text = m.message.conversation
  let id = m.key.remoteJid
  const isGroup = id.endsWith('@g.us')
  const totalchat = await conn.chats.all()
  const sender = isGroup ? m.participant : m.key.remoteJid
  const groupMetadata = isGroup ? await conn.groupMetadata(id) : ''
  const groupName = isGroup ? groupMetadata.subject : ''
  const desk = isGroup ? groupMetadata.desc : ''
  const groupId = isGroup ? groupMetadata.jid : ''
  const groupMembers = isGroup ? groupMetadata.participants : ''
  const messageType = Object.keys(messageContent)[0] // message will always contain one key signifying what kind of message
  let imageMessage = m.message.imageMessage;
  console.log(`[ ${moment().format("HH:mm:ss")} ] => Nomor: [ ${id.split("@s.whatsapp.net")[0]} ] => ${text}`);
//AUTO RESPON
 if (text == 'Bom dia'){
conn.sendMessage(id, 'Bom dia, em que posso ajudá-lo? se confuso, digite !menu sim a...' ,MessageType.text);
}
 if (text == 'Boa noite'){
conn.sendMessage(id, 'Boa noite, posso ajudar em alguma coisa? se confuso, digite !menu sim a...' ,MessageType.text);
}
 if (text == 'wtfd'){
conn.sendMessage(id, 'Nossa que isso me arrepiou safado.' ,MessageType.text);
}
 if (text == 'Oii'){
conn.sendMessage(id, 'Oi iai vai pagar um x-tudo ou nao ?...' ,MessageType.text);
}
 if (text == 'ainn'){
conn.sendMessage(id, 'Nossa que tesao vem me mamar todinha..' ,MessageType.text);
}
 if (text == 'Luan'){
conn.sendMessage(id, 'Nao fala meu criador aquele gostoso.' ,MessageType.text);
}
 if (text == 'Halo'){
conn.sendMessage(id, 'Hallo kak, Ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Asu'){
conn.sendMessage(id, 'Lu juga' ,MessageType.text);
}
 if (text == 'deni'){
conn.sendMessage(id, 'owner ganteng tuh' ,MessageType.text);
}
 if (text == 'Ngentod'){
conn.sendMessage(id, 'Pingin ngentod?' ,MessageType.text);
}
 if (text == 'Anjing'){
conn.sendMessage(id, 'Jangan toxic anjing' ,MessageType.text);
}
 if (text == 'Bacot'){
conn.sendMessage(id, 'lu bacot_-' ,MessageType.text);
}
 if (text == 'Test'){
conn.sendMessage(id, 'Test 1,2,3 ketik !menu' ,MessageType.text);
}
 if (text == 'Hai'){
conn.sendMessage(id, 'Hai juga, Ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Woi'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a..' ,MessageType.text);
} 
 if (text == 'Hi'){
conn.sendMessage(id, 'Hi juga, Ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Gan'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Sis'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a..' ,MessageType.text);
}
 if (text == 'Bro'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Min'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Sayang'){
conn.sendMessage(id, 'Iya sayang?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'I love u'){
conn.sendMessage(id, 'love you too' ,MessageType.text);
}
 if (text == 'Mas'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Mba'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Bre'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Cuy'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'Euy'){
conn.sendMessage(id, 'Ya?, ada yang bisa saya bantu? kalo bingung ketik !menu ya a...' ,MessageType.text);
}
 if (text == 'makasi'){
conn.sendMessage(id, 'Sama sama, semoga harimu menyenangkan :)' ,MessageType.text);
}
 if (text == 'Makasi'){
conn.sendMessage(id, 'Sama sama, semoga harimu menyenangkan :)' ,MessageType.text);
}
 if (text == 'makasih'){
conn.sendMessage(id, 'Sama sama, semoga harimu menyenangkan :)' ,MessageType.text);
}
 if (text == 'Makasih'){
conn.sendMessage(id, 'Sama sama, semoga harimu menyenangkan :)' ,MessageType.text);
}
 if (text == 'thank'){
conn.sendMessage(id, 'Sama sama, semoga harimu menyenangkan :)' ,MessageType.text);
}
 if (text == 'Thank'){
conn.sendMessage(id, 'Sama sama, semoga harimu menyenangkan :)' ,MessageType.text);
}
 if (text == 'thanks'){
conn.sendMessage(id, 'Sama sama, semoga harimu menyenangkan :)' ,MessageType.text);
}
 if (text == 'Thanks'){
conn.sendMessage(id, 'Sama sama, semoga harimu menyenangkan :)' ,MessageType.text);
}

//BISMILLAH DULU TOD
  if (text.includes('!menu')) {
    var nomor = m.participant
    const options = {
      text: `*Ola Amigo @${nomor.split("@s.whatsapp.net")[0]} Me Chamo ${BotName}*
╔════════════════════╗
║────〘 ${BotName}〙──────
╠════════════════════╝
║────〘 Dev Brasil Cod❤ 〙──────
╠════════════════════╝
║❖ *!owner*
║❖ *!donasi*
║❖ *!info*
╠════════════════════╗
║───〘 *Menu Do Bot* 〙──────
╠════════════════════╝
║❖️ *!tools*
║️❖ *!gabut*
║❖ *!game*
║❖ *!grup*
║❖ *!primbon*
║❖ *!random*
║❖ *!maker*
║❖ *!edukasi*
║❖ *!other*
║❖ *!download*
╠════════════════════╗
║──── *${BotName}* ──────
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║──── *${BotName}* ──────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`,
      contextInfo: { mentionedJid: [nomor] }
    }
    conn.sendMessage(id, options, MessageType.text, { quoted: m })
  }
//CREATOR
    if (text.includes('!owner')) {
    conn.sendMessage(id, { displayname: "Jeff", vcard: vcard }, MessageType.contact, { quoted: m })
    conn.sendMessage(id, `esse e o numero do dono do bot❤`, MessageType.text, { quoted: m })
  }
//DONASI
  if (text.includes('!donasi')) {
    conn.sendMessage(id, `Ajude a doar para manter o bot funcionando.

 اتَّقوا النَّارَ ولو بشقِّ تمرةٍ ، فمن لم يجِدْ فبكلمةٍ طيِّبةٍ
_ “Afasta-te dos fogos do inferno, nem que seja dando esmola a tamareira (um pouco). Se você não tem, então você pode dizer thayyibah” [HR. Bukhari 6539, Muslim 1016]_

╔════════════════════╗
║ *DOE PARA  ${BotName}*
╠════════════════════╝
║╭──❉ *DOE BOS* ❉─────
║│❖ *OVO*: _${ovo}_
║│❖ *DANA*: _${dana}_
║│❖ *PULSA*: _${pulsa}_
║│❖ *GOPAY*: _${gopay}_
║╰──────────────────
╠════════════════════╗
║         *${BotName}*
║  ▌│█║▌║▌║║▌║▌║█│▌
║  ▌│█║▌║▌║║▌║▌║█│▌
║         *${BotName}*
╠════════════════════╝
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//INFO
  if (text.includes('!info')) {
    var nomor = m.participant
    const options = {
      text: `*Olá @${nomor.split("@s.whatsapp.net")[0]} Eu sou ${BotName}*
         ────────────────
➢ Official group 
  _${wa}_
         ────────────────
╔════════════════════╗
║─────〘  *INFOR* 〙──────
╠════════════════════╝
║❖️ Proprietario: *${ow}*
║️❖ Prefixo:  *「 ! 」*
║❖ Ativo : *${aktif} WIB*
║❖ Grupo:  *${groupName}*
╠════════════════════╗
║───── *${BotName}* ─────
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║───── *${BotName}* ─────
╠════════════════════╝
╠════════════════════╗
║SIGA MEU INSTAGRAM
║ _${instagram}_
╚════════════════════╝`,
      contextInfo: { mentionedJid: [nomor] }
    }
    conn.sendMessage(id, options, MessageType.text, { quoted: m })
  }
//SIMPLE MENU
  else if (text == '!tools') {
    conn.sendMessage(id, `
╔════════════════════╗
║───〘  *POPULAR* 〙─────
╠════════════════════╝
║❖ *!stiker*
║❖ *!nulis*
║❖ *!stalkig*
║❖ *!ssweb*
║❖ *!simi*
║❖ *!quotes*
║❖ *!bikinquote*
╠════════════════════╗
║───── *${BotName}* ─────
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║───── *${BotName}* ─────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//SIMI
  if (text.includes("!simi")) {
    const teks = text.replace(/!simi /, "")
    axios.get(`https://st4rz.herokuapp.com/api/simsimi?kata=${teks}`).then((res) => {
      let hasil = `*${res.data.result}*`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//STICKER
  if (text.includes('!Stiker')) {
    conn.sendMessage(id, 'Envie fotos com legendas !stiker ...', MessageType.text, { quoted: m });
  }
  if (messageType == 'imageMessage') {
    let caption = imageMessage.caption.toLocaleLowerCase()
    const buffer = await conn.downloadMediaMessage(m) // to decrypt & use as a buffer
    if (caption == '!stiker') {
      const stiker = await conn.downloadAndSaveMediaMessage(m) // to decrypt & save to file

      const
        {
          exec
        } = require("child_process");
      exec('cwebp -q 50 ' + stiker + ' -o temp/' + jam + '.webp', (error, stdout, stderr) => {
        let stik = fs.readFileSync('temp/' + jam + '.webp')
        conn.sendMessage(id, stik, MessageType.sticker, { quoted: m })
      });
    }
    if (caption == '!sticker') {
      const stiker = await conn.downloadAndSaveMediaMessage(m) // to decrypt & save to file
      const
        {
          exec
        } = require("child_process");
      exec('cwebp -q 50 ' + stiker + ' -o temp/' + jam + '.webp', (error, stdout, stderr) => {
        let stik = fs.readFileSync('temp/' + jam + '.webp')
        conn.sendMessage(id, stik, MessageType.sticker, { quoted: m })
      });
    }
  }
//BIKIN QUOTES
  if (text.includes('!bikinquote')) {
    const gh = text.split("!bikinquote ")[1];
    const kata = gh.split("&")[0];
    const author = gh.split("&")[1];
    axios.get(`https://terhambar.com/aw/qts/?kata=${kata}&author=${author}&tipe=rain`)
      .then((res) => {
        imageToBase64(res.data.result)
          .then(
            (ress) => {
              conn.sendMessage(id, 'espere uma cotação...', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { quoted: m })
            })
      })
  }
//NULIS
  if (text.includes('!nulis')) {
    const teks = text.replace(/!nulis /, '')
    axios.get(`https://mhankbarbar.tech/nulis?text=${teks}&apiKey=${apibarbar}`)
      .then((res) => {
        imageToBase64(res.data.result)
          .then(
            (ress) => {
              conn.sendMessage(id, 'Paciência a', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { caption: 'Lain kali nulis sendiri a', quoted: m })
            })
      })
  }
//STALK IG
  if (text.includes("!stalkig")) {
    const sons = text.replace(/!stalkig /, "")

    axios.get(`https://docs-jojo.herokuapp.com/api/stalk?username=${sons}`).then((res) => {
      imageToBase64(res.data.graphql.user.profile_pic_url_hd)
        .then(
          (ress) => {
            var buf = Buffer.from(ress, 'base64')
            conn.sendMessage(id, 'espere um, não se esqueça de seguir Luan Pereira_', MessageType.text, { quoted: m })
            let hasil = `*>Nome do usuario* : ${res.data.graphql.user.username}\n*>Nome* : ${res.data.graphql.user.full_name}\n*>Seguidores* : ${res.data.graphql.user.edge_followed_by.count}\n*>Categoria* : ${res.data.graphql.user.category_name}\n*>Segue* : ${res.data.graphql.user.edge_follow.count}\n*>Numero de Postagem* : ${res.data.graphql.user.edge_owner_to_timeline_media.count}\n*>Destaques* : ${res.data.graphql.user.highlight_reel_count}\n*>Bio* : ${res.data.graphql.user.biography}\n*>Externo url* = ${res.data.graphql.user.external_url}\n\n*Segue* : ${instagram}`;
            conn.sendMessage(id, buf, MessageType.image, { caption: hasil, quoted: m });
          })
    })
  }
//QUOTES
  if (text.includes("!quotes")) {
    var items = ["sajak rindu", "Kata kata bucin", "kata kata motivasi", "kata kata romantis", "quotes bucin"];
    var nime = items[Math.floor(Math.random() * items.length)];
    var url = "https://api.fdci.se/rep.php?gambar=" + nime;

    axios.get(url)
      .then((result) => {
        var n = JSON.parse(JSON.stringify(result.data));
        var nimek = n[Math.floor(Math.random() * n.length)];
        imageToBase64(nimek)
          .then(
            (response) => {
              conn.sendMessage(id, 'espere um minuto...', MessageType.text, { quoted: m })
              var buf = Buffer.from(response, 'base64');
              conn.sendMessage(id, buf, MessageType.image, { caption: `Nih a`, quoted: m })
            }
          )
          .catch(
            (error) => {
              console.log(error);
            }
          )
      });
  }
//SS WEB
  else if (text.startsWith('!ssweb')) {
    let linknyo = text.replace('!ssweb ', "");
    let client = conn;
    if (linknyo.includes('.')) {
      axios.get(`https://api-mwmaulana310.herokuapp.com/ssweb?src=${linknyo}`)
        .then(res => {
          let resData = res.data.resultNosplit;
          let buffer = Buffer.from(resData, 'base64')
          client.sendMessage(id, buffer, MessageType.image, { quoted: m, caption: `nih a...` })
        })
        .catch(err => client.sendMessage(id, `O link esta realmente batendo!`, MessageType.text, { quoted: m }))
    } else {
      conn.sendMessage(id, `Lahh nao e um link de sexo!`, MessageType.text, { quoted: m })
    }
  }
//GAME MENU
  else if (text == '!game') {
    conn.sendMessage(id, `
╔════════════════════
║─────〘  *Game* 〙─────
╠════════════════════
║❖ *!tebakgambar*
║❖ *!family100*
║❖ *!truth*
║❖ *!dare*
║❖ *!apakah*
║❖ *!bolehkah*
║❖ *!kapan*
╠════════════════════╗
║───── *${BotName}* ───── 
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║───── *${BotName}* ─────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//TEBAK GAMBAR
  if (text.includes("!tebakgambar")) {
    axios.get(`https://api.vhtear.com/tebakgambar&apikey=${apivhtear}`).then((res) => {
      imageToBase64(res.data.result.soalImg)
        .then(
          (ress) => {
            conn.sendMessage(id, 'seja paciente, se você não pode doar, hein?', MessageType.text, { quoted: m })
            var buf = Buffer.from(ress, 'base64')
            conn.sendMessage(id, buf, MessageType.image, { quoted: m })
          })
    })
  }

//FAMILY 100
  if (text.includes("!family100")) {
    axios.get(`https://api.vhtear.com/family100&apikey=${apivhtear}`).then((res) => {
      let hasil = `*Pertinyiinnyi* : ${res.data.result.soal}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//TRUTH OR DARE
  if (messageType === MessageType.text) {
    let is = m.message.conversation.toLocaleLowerCase()
    if (is == '!truth') {
      fetch('https://raw.githubusercontent.com/mrfzvx12/random-scraper/main/random/truth.txt')
        .then(res => res.text())
        .then(body => {
          let tod = body.split("\n");
          let pjr = tod[Math.floor(Math.random() * tod.length)];
          let pantun = pjr.replace(/pjrx-line/g, "\n");
          conn.sendMessage(id, pantun, MessageType.text, { quoted: m })
        });
    }
  };

  if (messageType === MessageType.text) {
    let is = m.message.conversation.toLocaleLowerCase()
    if (is == '!dare') {
      fetch('https://raw.githubusercontent.com/mrfzvx12/random-scraper/main/random/dare.txt')
        .then(res => res.text())
        .then(body => {
          let tod = body.split("\n");
          let pjr = tod[Math.floor(Math.random() * tod.length)];
          let pantun = pjr.replace(/pjrx-line/g, "\n");
          conn.sendMessage(id, pantun, MessageType.text, { quoted: m })
        });
    }
  };
//KERANG AJAIB
  if (text.includes('!apakah')) {
    const teks = text.replace(/!/, '')
    const truth = [
      'sim',
      'Não',
      'Pode ser',
      'Tente perguntar novamente',
      'Talvez',
      '🤐']
    const ttrth = truth[Math.floor(Math.random() * truth.length)]
    conn.sendMessage(id, 'Pergunta : *' + teks + '*\n\n Responda : ' + ttrth, MessageType.text, { quoted: m })
  }

  if (text.includes('!bolehkah')) {
    const teks = text.replace(/!/, '')
    const truth = [
      'Maio',
      'Não deveria',
      'Altamente recomendado',
      'Tente perguntar novamente',
      'Não',
      'Talvez',
      'Não',
      '🤐']
    const ttrth = truth[Math.floor(Math.random() * truth.length)]
    conn.sendMessage(id, 'Pergunta : *' + teks + '*\n\nResposta : ' + ttrth, MessageType.text, { quoted: m })
  }


  if (text.includes('!kapan')) {
    const teks = text.replace(/!/, '')
    const truth = [
      'Mais 1 dia',
      'Mais 2 dias',
      'Mais 3 dias',
      'Mais 4 dias',
      'Mais 5 dias',
      'Mais 6 dias',
      'Falta 1 semana',
      'Mais 2 semanas',
      '3 semanas para ir',
      '1 mês a mais',
      'Mais 2 meses',
      'mais 3 dias',
      '4 meses',
      '5 meses',
      'Mais 6 dias',
      '7 meses para ir',
      '8 meses para ir',
      'Mais 9 dias',
      '10 meses para ir',
      '11 meses para ir',
      '1 tahun lagi',
      'Mais 2 anos',
      'Mais 3 anos',
      'Mais 4 anos',
      'Não vou',
      'Com certeza vai acontecer ?',
      'eu duvido',
      'O dia Depois de Amanhã',
      'Fim do próximo mês',
      'No início do próximo mês',
      'Próximo ano',
      'Próximo mês',
      'Em breve',
      '🤐']
    const ttrth = truth[Math.floor(Math.random() * truth.length)]
    conn.sendMessage(id, 'Pergunta : *' + teks + '*\n\nResposta : ' + ttrth, MessageType.text, { quoted: m })
  }
//MENU GROUP
  else if (text == '!grup') {
    conn.sendMessage(id, `
╔════════════════════╗
║─────〘  *Grupo* 〙──────
╠════════════════════╝
║❖ *!tagme*
║❖ *!setname*
║❖ *!setdesc*
║❖ *!opengrup*
║❖ *!closegrup*
║❖ *!linkgrup*
║❖ *!rules*
║❖ *!notif*
╠════════════════════╗
║──── *${BotName}* ──────
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║──── *${BotName}* ──────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//TAGME
  if (text.includes('!tagme')) {
    var nomor = m.participant
    const options = {
      text: `@${nomor.split("@s.whatsapp.net")[0]} Oi bebe`,
      contextInfo: { mentionedJid: [nomor] }
    }
    conn.sendMessage(id, options, MessageType.text)
  }
//NAMA GRUP
  if (text.includes("!setname")) {
    const teks = text.replace(/!setname /, "")
    let nama = `${teks}`;
    let idgrup = `${id.split("@s.whatsapp.net")[0]}`;
    conn.groupUpdateSubject(idgrup, nama);
    conn.sendMessage(id, 'Renomeando o Grupo', MessageType.text, { quoted: m });
  }
//DESK GRUP
  if (text.includes("!setdesc")) {
    const teks = text.replace(/!setdesc /, "")
    let desk = `${teks}`;
    let idgrup = `${id.split("@s.whatsapp.net")[0]}`;
    conn.groupUpdateDescription(idgrup, desk)
    conn.sendMessage(id, 'Mudando a descrição do grupo', MessageType.text, { quoted: m });
  }
//BUKA GRUP
  else if (text == '!opengrup') {
    let hasil = `${id.split("@s.whatsapp.net")[0]}`;
    conn.groupSettingChange(hasil, GroupSettingChange.messageSend, false);
    conn.sendMessage(id, MessageType.text);
  }
//TUTUP GRUP
  else if (text == '!closegrup') {
    let hasil = `${id.split("@s.whatsapp.net")[0]}`;
    conn.groupSettingChange(hasil, GroupSettingChange.messageSend, true);
    conn.sendMessage(id, MessageType.text);
  }
//LINK GRUP
  if (text.includes("!linkgrup")) {
    const linkgc = await conn.groupInviteCode(id)
    const hasil = `Grupo : ${groupName}\n*Link* : https://chat.whatsapp.com/${linkgc}`;
    conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
  }
//NOTIF GRUP
  if (text.includes('!notif')) {
    const value = text.replace(/!notif /, '')
    var nomor = m.participant
    const group = await conn.groupMetadata(id)
    const member = group['participants']
    const ids = []
    member.map(async adm => {
      ids.push(adm.id.replace('c.us', 's.whatsapp.net'))
    })
    const options = {
      text: `Anuncio de @${nomor.split("@s.whatsapp.net")[0]}\n*Mensagem : ${value}*`,
      contextInfo: { mentionedJid: ids },
      quoted: m
    }
    conn.sendMessage(id, options, MessageType.text)
  }
//RULES GRUP
  if (text.includes("!rules")) {
    let idgrup = `*${groupName}*\n*Regras* : \n${desk}`;
    conn.sendMessage(id, idgrup, MessageType.text, { quoted: m });
  }
//MENU FUN
  else if (text == '!gabut') {
    conn.sendMessage(id, `
╔════════════════════╗
║────〘  *PESSOAS* 〙─────
╠════════════════════╝
║❖ *!pantun*
║❖ *!receh*
║❖ *!bapak*
║❖ *!gombal*
║❖ *!motivasi* ${eror}
║❖ *!infoanime* ${eror}
║❖ *!puisi1* ${eror}
║❖ *!puisi2* ${eror}
║❖ *!puisi3* ${eror}
║❖ *!cerpen* ${eror}
║❖ *!seberapagay* ${eror}
║❖ *!prankchat*
║❖ *!alay*
╠════════════════════╗
║──── *${BotName}* ──────
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║──── *${BotName}* ──────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//PANTUN
  if (messageType === MessageType.text) {
    let is = m.message.conversation.toLocaleLowerCase()

    if (is == '!pantun') {
      fetch('https://raw.githubusercontent.com/pajaar/grabbed-results/master/pajaar-2020-pantun-pakboy.txt')
        .then(res => res.text())
        .then(body => {
          let tod = body.split("\n");
          let pjr = tod[Math.floor(Math.random() * tod.length)];
          let pantun = pjr.replace(/pjrx-line/g, "\n");
          conn.sendMessage(id, pantun, MessageType.text, { quoted: m })
        });
    }
  };
//RECEH
  if (messageType === MessageType.text) {
    let is = m.message.conversation.toLocaleLowerCase()
    if (is == '!receh') {
      fetch('https://raw.githubusercontent.com/mrfzvx12/random-scraper/main/random/receh.txt')
        .then(res => res.text())
        .then(body => {
          let tod = body.split("\n");
          let pjr = tod[Math.floor(Math.random() * tod.length)];
          let pantun = pjr.replace(/pjrx-line/g, "\n");
          conn.sendMessage(id, pantun, MessageType.text, { quoted: m })
        });
    }
  };
//BAPACK
  if (messageType === MessageType.text) {
    let is = m.message.conversation.toLocaleLowerCase()
    if (is == '!bapak') {
      fetch('https://raw.githubusercontent.com/mrfzvx12/random-scraper/main/random/statusbapack.txt')
        .then(res => res.text())
        .then(body => {
          let tod = body.split("\n");
          let pjr = tod[Math.floor(Math.random() * tod.length)];
          let pantun = pjr.replace(/pjrx-line/g, "\n");
          conn.sendMessage(id, pantun, MessageType.text, { quoted: m })
        });
    }

  };
//GOMBAL
  if (messageType === MessageType.text) {
    let is = m.message.conversation.toLocaleLowerCase()
    if (is == '!gombal') {
      fetch('https://raw.githubusercontent.com/mrfzvx12/random-scraper/main/random/gombal.txt')
        .then(res => res.text())
        .then(body => {
          let tod = body.split("\n");
          let pjr = tod[Math.floor(Math.random() * tod.length)];
          let pantun = pjr.replace(/pjrx-line/g, "\n");
          conn.sendMessage(id, pantun, MessageType.text, { quoted: m })
        });
    }

  };
//MOTIVASI
  if (text.includes("!motivasi")) {
    const teks = text.replace(/!motivasi /, "")
    axios.get(`https://kocakz.herokuapp.com/api/random/text/katabijak`).then((res) => {
      let hasil = `${res.data.result}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
// INFO ANIME
  if (text.includes("!infoanime")) {
    const sons = text.replace(/!infonime /, "")
    axios.get(`https://arugaz.herokuapp.com/api/kuso?q=${sons}`).then((res) => {
      conn.sendMessage(id, 'Espere um minuto...', MessageType.text, { quoted: m })
      let hasil = `*Titulo* : ${res.data.title}\n*Informacoes* : ${res.data.info}\n*Link* : ${res.data.link_dl}\n*Sinopse* : ${res.data.sinopsis}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//PUISI
  if (text.includes("!puisi1")) {
    axios.get(`https://arugaz.herokuapp.com/api/puisi1`).then((res) => {
      conn.sendMessage(id, 'Paciência amigo...', MessageType.text, { quoted: m })
      let hasil = `${res.data.result}`
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m })
    })
  }

  if (text.includes("!puisi2")) {
    axios.get(`https://arugaz.herokuapp.com/api/puisi2`).then((res) => {
      conn.sendMessage(id, 'Paciência amigo...', MessageType.text, { quoted: m })
      let hasil = `${res.data.result}`
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m })
    })
  }

  if (text.includes("!puisi3")) {
    axios.get(`https://arugaz.herokuapp.com/api/puisi3`).then((res) => {
      conn.sendMessage(id, 'Paciência amigo...', MessageType.text, { quoted: m })
      let hasil = `${res.data.result}`
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m })
    })
  }

//CERPEN
  if (text.includes("!cerpen")) {
    axios.get(`https://arugaz.herokuapp.com/api/cerpen`).then((res) => {
      conn.sendMessage(id, '[ 📌 ] Procurando contos por favor aguarde...🔎', MessageType.text, { quoted: m })
      let hasil = `${res.data.result}`
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m })
    })
  }
//SEBERAPAGAY
  if (text.includes("!seberapagay")) {
    const teks = text.replace(/!seberapagay /, "")
    axios.get(`https://arugaz.herokuapp.com/api/howgay`).then((res) => {
      let hasil = `*Gay Detectado*\n*Porcentagem* : ${res.data.persen}%\n${res.data.desc}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//CHAT KOSONG
  if (text.includes('!prankchat')) {
    const gh = text.split("!prankchat ")[1];
    const nama = gh.split("&")[0];
    const tgl = gh.split("&")[1];
    let hasil = `${nama}͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏${tgl}`;
    conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
  }
//FONT ALAY
  if (text.includes("!alay")) {
    const alay = text.split("!alay")[1]
    axios.get(`https://api.terhambar.com/bpk?kata=${alay}`).then((res) => {
      let hasil = `${res.data.text}`
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m })
    })
  }
//MENU DOWNLOAD
  else if (text == '!download') {

    conn.sendMessage(id, `
╔════════════════════╗
║────〘  *Download* 〙────
╠════════════════════╝
║❖️ *!ytmp3* ${eror}
║️❖ *!yutubdl* ${eror}
║️❖ *!twitdl*
║️❖ *!ig*
║️❖ *!fb* ${eror}
║❖ *!tiktod* ${eror}
║❖ *!joox*
╠════════════════════╗
║──── *${BotName}* ────── 
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║───── *${BotName}* ─────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//YT MP3
  if (text.includes('!ytmp3')) {
    const teks = text.replace(/!ytmp3 /, "")
    axios.get(`https://kocakz.herokuapp.com/api/media/ytaudio?url=${teks}`).then((res) => {
      imageToBase64(res.data.result.thumb)
        .then(
          (ress) => {
            var buf = Buffer.from(ress, 'base64')
            conn.sendMessage(id, 'espera um paciente...', MessageType.text, { quoted: m })
            let hasil = `*Judul* : ${res.data.result.title}\n*Ukuran* : ${res.data.result.filesizeF}\n*Format* : MP3\n*Link* : ${res.data.result.dl_link}`;
            conn.sendMessage(id, buf, MessageType.image, { caption: hasil, quoted: m });
          })
    })
  }
//YT MP4
  if (text.includes('!yutubdl')) {
    const teks = text.replace(/!yutubdl /, "")
    axios.get(`https://kocakz.herokuapp.com/api/media/ytvideo?url=${teks}`).then((res) => {
      imageToBase64(res.data.result.thumb)
        .then(
          (ress) => {
            var buf = Buffer.from(ress, 'base64')
            conn.sendMessage(id, 'espera um paciente...', MessageType.text, { quoted: m })
            let hasil = `*Titulo* : ${res.data.result.title}\n*Tamanho* : ${res.data.result.filesizeF}\n*Formato* : MP4\n*Link* : ${res.data.result.dl_link}`;
            conn.sendMessage(id, buf, MessageType.image, { caption: hasil, quoted: m });
          })
    })
  }
//TWITER DOWNLOAD
  if (text.includes('!twitdl')) {
    const teks = text.replace(/!twitdl /, "")
    axios.get(`https://mhankbarbar.tech/api/twit?url=${teks}&apiKey=${apibarbar}`).then((res) => {
      conn.sendMessage(id, '[ 📌 ] Baixando aguarde...🔎', MessageType.text, { quoted: m })
      let hasil = `Clique no link e baixe os resultados!\n*Link* : ${res.data.result}\n*Titulo* : ${res.data.title}\n${res.data.quote}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });

    })
  }
//IG DOWNLOAD
  if (text.includes('!ig')) {
    const teks = text.replace(/!ig /, "")
    axios.get(`https://mhankbarbar.tech/api/ig?url=${teks}&apiKey=${apibarbar}`).then((res) => {
      conn.sendMessage(id, '[ 📌 ] Baixando aguarde...🔎', MessageType.text, { quoted: m })
      let hasil = `Clique o link e baixe o resultado!\n*Link* : ${res.data.result}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }


//TIKTOK DOWNLOAD
  if (text.includes('!tiktod')) {
    const teks = text.replace(/!tiktod /, "")
    axios.get(`https://kocakz.herokuapp.com/api/media/tiktok?url=${teks}`).then((res) => {
      conn.sendMessage(id, '[ 📌 ] Baixando  aguarde...🔎', MessageType.text, { quoted: m })
      let hasil = `*Nome* : ${res.data.nameInfo}\n*Rubrica* : ${res.data.textInfo}\n*Tempo* : ${res.data.timeInfo}\n*Link* : ${res.data.mp4direct}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }

//FB DOWNLOAD
  if (text.includes('!fb')) {
    const teks = text.replace(/!fb /, "")
    axios.get(`https://kocakz.herokuapp.com/api/media/facebook?url=${teks}`).then((res) => {

      conn.sendMessage(id, '[ 📌 ] Baixando  aguarde...🔎', MessageType.text, { quoted: m })
      let hasil = `*Link* : ${res.data.linkHD}`;
      conn.sendMessage(id, buf, MessageType.text, { caption: hasil, quoted: m });
    })
  }
//JOOX DOWNLOAD
  if (text.includes('!joox')) {
    const teks = text.replace(/!joox /, "")
    axios.get(`https://tobz-api.herokuapp.com/api/joox?q=${teks}&apikey=${tobzkey}`).then((res) => {
      imageToBase64(res.data.result.thumb)
        .then(
          (ress) => {
            var buf = Buffer.from(ress, 'base64')
            var lagu = `{url: ${res.data.result.mp3} ,}`;
            conn.sendMessage(id, '[ 📌 ] Baixando  aguarde...🔎', MessageType.text, { quoted: m })
            let hasil = `Aqui tod!\n*Titulo* : ${res.data.result.album} - ${res.data.result.judul}\n*Link* : ${res.data.result.mp3}`;
            conn.sendMessage(id, buf, MessageType.image, { quoted: m, caption: hasil })
            conn.sendMessage(id, lagu, MessageType.audio, { mimetype: 'audio/mp4', filename: `${data.result.judul}.mp3`, quoted: m })
          })
    })
  }
//MENU PRIMBON
  else if (text == '!primbon') {
    conn.sendMessage(id, `
╔════════════════════╗
║───〘  *Horoscopo* 〙──────
╠════════════════════╝
║➸️ *!artinama* ${eror}
║➸️ *!artijodoh* ${eror}
║➸️ *!artimimpi*
║➸️ *!zodiak*
╠════════════════════╗
║──── *${BotName}* ────── 
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║──── *${BotName}* ──────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝ `, MessageType.text, { quoted: m });
  }
//ARTI NAMA
  if (text.includes("!artinama")) {
    const teks = text.replace(/!artinama /, "")
    axios.get(`https://arugaz.herokuapp.com/api/artinama?nama=${teks}`).then((res) => {
      let hasil = `*Significado do seu nome e*\n\n    *${teks}* ${res.data.result}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//ARTI JODOH
  if (text.includes('!artijodoh')) {
    const gh = text.split("!artijodoh ")[1];
    const lu = gh.split("&")[0];
    const doi = gh.split("& ")[1];
    axios.get(`https://arugaz.herokuapp.com/api/jodohku?nama=${lu}&pasangan=${doi}`)
      .then((res) => {
        let hasil = `*Correspondencias por nome*\n\n   *Nome* : ${res.data.nama}\n   *Casal* : ${res.data.pasangan}\n\n*Positivo* : ${res.data.positif}\n*Negativo* : ${res.data.negatif}`;
        conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
      })
  }
//ARTI MIMPI
  if (text.includes("!artimimpi")) {
    const teks = text.replace(/!artimimpi /, "")
    axios.get(`https://api.vhtear.com/artimimpi?query=${teks}&apikey=${apivhtear}`).then((res) => {
      let hasil = `${res.data.result.hasil}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//ZODIAK
  if (text.includes("!zodiak")) {
    const teks = text.replace(/!zodiak /, "")
    axios.get(`https://api.vhtear.com/zodiak?query=${teks}&apikey=${apivhtear}`).then((res) => {
      let hasil = `*Zodiak* : ${res.data.result.zodiak}\n*Previsao hari ini* :\n${res.data.result.ramalan}\n\n_${res.data.result.inspirasi}_`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//MENU RANDOM
  else if (text == '!random') {
    conn.sendMessage(id, `
╔════════════════════╗
║────〘  *ALEATORIA* 〙────
╠════════════════════╝
║❖ *!gacha cowok*
║❖ *!gacha cewek*
║❖ *!randomanime*
║❖ *!nekonime*
║❖ *!meme*
║❖ *!loli*
║❖ *!wphd*
╠════════════════════╗
║───── *${BotName}* ─────
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║───── *${BotName}* ─────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//GACHA CEWEK
  if (text.includes("!gacha cewek")) {
    var items = ["ullzang girl", "cewe cantik", "cewe hijab", "remaja cantik", "cewek jepang"];
    var cewe = items[Math.floor(Math.random() * items.length)];
    var url = "https://api.fdci.se/rep.php?gambar=" + cewe;

    axios.get(url)
      .then((result) => {
        var b = JSON.parse(JSON.stringify(result.data));
        var cewek = b[Math.floor(Math.random() * b.length)];
        imageToBase64(cewek) // Path to the image
          .then(
            (response) => {
              conn.sendMessage(id, 'Espere um minuto, procure por isso?', MessageType.text, { quoted: m })
              var buf = Buffer.from(response, 'base64'); // Ta-da	
              conn.sendMessage(id, buf, MessageType.image, { caption: `nih a`, quoted: m })

            }
          )
          .catch(
            (error) => {
              console.log(error); // Logs an error if there was one
            }
          )

      });
  }

//GACHA COWOK
  if (text.includes("!gacha cowok")) {
    var items = ["cowo ganteng", "cogan", "cowok indonesia ganteng", "cowo keren"];
    var cowo = items[Math.floor(Math.random() * items.length)];
    var url = "https://api.fdci.se/rep.php?gambar=" + cowo;

    axios.get(url)
      .then((result) => {
        var z = JSON.parse(JSON.stringify(result.data));
        var cowok = z[Math.floor(Math.random() * z.length)];
        imageToBase64(cowok)
          .then(
            (response) => {
              conn.sendMessage(id, 'espere bebe, estou procurando por um cara primeiro', MessageType.text, { quoted: m })
              var buf = Buffer.from(response, 'base64');
              conn.sendMessage(id, buf, MessageType.image, { caption: `nih beb, tapi gantengan deniambrose_`, quoted: m })
            }
          )
          .catch(
            (error) => {
              console.log(error);
            }
          )

      });
  }
//RANDOM ANIME
  if (text.includes("!randomanime")) {
    var items = ["anime tumblr", "anime loli", "anime aesthetic", "anime hd"];
    var nime = items[Math.floor(Math.random() * items.length)];
    var url = "https://api.fdci.se/rep.php?gambar=" + nime;

    axios.get(url)
      .then((result) => {
        var n = JSON.parse(JSON.stringify(result.data));
        var nimek = n[Math.floor(Math.random() * n.length)];
        imageToBase64(nimek)
          .then(
            (response) => {
              conn.sendMessage(id, '[ 📌 ] Procurando por anime por favor espere...🔎', MessageType.text, { quoted: m })
              var buf = Buffer.from(response, 'base64');
              conn.sendMessage(id, buf, MessageType.image, { caption: `asik ada wibu`, quoted: m })
            }
          )
          .catch(
            (error) => {
              console.log(error);
            }
          )

      });
  }
//RANDOM LOLI
  if (text.includes("!loli")) {
    var items = ["anime loli"];
    var nime = items[Math.floor(Math.random() * items.length)];
    var url = "https://api.fdci.se/rep.php?gambar=" + nime;

    axios.get(url)
      .then((result) => {
        var n = JSON.parse(JSON.stringify(result.data));
        var nimek = n[Math.floor(Math.random() * n.length)];
        imageToBase64(nimek)
          .then(
            (response) => {
              conn.sendMessage(id, 'Espere um minuto...', MessageType.text, { quoted: m })
              var buf = Buffer.from(response, 'base64');
              conn.sendMessage(id, buf, MessageType.image, { caption: `nih loli jangan ange`, quoted: m })
            }
          )
          .catch(
            (error) => {
              console.log(error);
            }
          )
      });
  }

//RANDOM NEKONIME
  if (text.includes("!nekonime")) {
    var items = ["anime neko"];
    var nime = items[Math.floor(Math.random() * items.length)];
    var url = "https://api.fdci.se/rep.php?gambar=" + nime;

    axios.get(url)
      .then((result) => {
        var n = JSON.parse(JSON.stringify(result.data));
        var nimek = n[Math.floor(Math.random() * n.length)];
        imageToBase64(nimek)
          .then(
            (response) => {
              conn.sendMessage(id, 'Espere um minuto...', MessageType.text, { quoted: m })
              var buf = Buffer.from(response, 'base64');
              conn.sendMessage(id, buf, MessageType.image, { caption: `Nihh a`, quoted: m })
            }
          )
          .catch(
            (error) => {
              console.log(error);
            }
          )
      });
  }
//RANDOM WALPAPER
  if (text.includes("!wphd")) {
    var items = ["wallpaper aesthetic", "wallpaper tumblr"];
    var nime = items[Math.floor(Math.random() * items.length)];
    var url = "https://api.fdci.se/rep.php?gambar=" + nime;

    axios.get(url)
      .then((result) => {
        var n = JSON.parse(JSON.stringify(result.data));
        var nimek = n[Math.floor(Math.random() * n.length)];
        imageToBase64(nimek)
          .then(
            (response) => {
              conn.sendMessage(id, 'espere mano, btw o papel de parede é aleatório...', MessageType.text, { quoted: m })
              var buf = Buffer.from(response, 'base64');
              conn.sendMessage(id, buf, MessageType.image, { quoted: m })
            }
          )
          .catch(
            (error) => {
              console.log(error);
            }
          )
      });
  }
//RANDOM MEME
  if (text.includes("!meme")) {
    var items = ["meme indonesia", "meme indo", "foto lucu", "meme spongebob"];
    var nime = items[Math.floor(Math.random() * items.length)];
    var url = "https://api.fdci.se/rep.php?gambar=" + nime;

    axios.get(url)
      .then((result) => {
        var n = JSON.parse(JSON.stringify(result.data));
        var nimek = n[Math.floor(Math.random() * n.length)];
        imageToBase64(nimek)
          .then(
            (response) => {
              conn.sendMessage(id, 'Por favor seja paciente primeiro', MessageType.text, { quoted: m })
              var buf = Buffer.from(response, 'base64');
              conn.sendMessage(id, buf, MessageType.image, { quoted: m })
            }
          )
          .catch(
            (error) => {
              console.log(error);
            }
          )
      });
  }
//MENU EDUCATION
  else if (text == '!edukasi') {
    conn.sendMessage(id, `
╔════════════════════╗
║────〘  *Educacao* 〙─────
╠════════════════════╝
║❖ *!brainly*
║❖ *!quran*
║❖ *!ngaji*
║❖ *!wiki*
║❖ *!covid*
║❖ *!faktaunik*
║❖ *!Kbbi*
╠════════════════════╗
║──── *${BotName}* ──────
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║──── *${BotName}* ──────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//BRAINLY
  if (text.includes('!brainly')) {
    const teks = text.replace(/!brainly /, "")
    axios.get(`https://api.vhtear.com/branly?query=${teks}&apikey=${apivhtear}`).then((res) => {
      let hasil = ` ͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏͏ ${res.data.result.data}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//RANDOM AL QURAN
  else if (text == '!quran') {
    axios.get('https://api.banghasan.com/quran/format/json/acak').then((res) => {
      const sr = /{(.*?)}/gi;
      const hs = res.data.acak.id.ayat;
      const ket = `${hs}`.replace(sr, '');
      let hasil = `[${ket}]   ${res.data.acak.ar.teks}\n\n${res.data.acak.id.teks}(QS.${res.data.surat.nama}, Ayat ${ket})`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//NGAJI SURAH
  if (text.includes("!ngaji")) {
    const teks = text.replace(/!ngaji /, "")
    axios.get(`https://api.vhtear.com/quran?no=${teks}&apikey=${apivhtear}`).then((res) => {
      let hasil = `*Sura* : ${res.data.result.surah}\n${res.data.result.quran}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//WIKIPEDIA
  if (text.includes("!wiki")) {
    const teks = text.replace(/!wiki /, "")
    axios.get(`https://alfians-api.herokuapp.com/api/wiki?q=${teks}`).then((res) => {
      conn.sendMessage(id, '[ 📌 ] Procurando aguarde um minuto...🔎', MessageType.text, { quoted: m })
      let hasil = `De acordo com a Wikipedia:\n\n${res.data.result}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//COVID 19
  if (text.includes("!covid")) {
    const get = require('got')
    const body = await get.post('https://api.kawalcorona.com/indonesia', {
    }).json();
    var positif = (body[0]['positif']);
    var sembuh = (body[0]['sembuh']);
    var meninggal = (body[0]['meninggal']);
    var dirawat = (body[0]['dirawat']);
    console.log(body[0]['name'])
    conn.sendMessage(id, `😷ULTIMOS DADOS DO DISTRITO COVID-19 DA INDONÉSIA\n\n*Positivo* = ${positif} \n*Curado* = ${sembuh} \n*Morreu* = ${meninggal}\n*Ser Tratado* = ${dirawat}\n\n*Fique seguro e sempre use uma máscara ao viajar*`, MessageType.text, { quoted: m });
  }
//FAKTA UNIK
  if (messageType === MessageType.text) {
    let is = m.message.conversation.toLocaleLowerCase()
    if (is == '!faktaunik') {
      fetch('https://raw.githubusercontent.com/ArugaZ/grabbed-results/main/random/faktaunix.txt')
        .then(res => res.text())
        .then(body => {
          let tod = body.split("\n");
          let pjr = tod[Math.floor(Math.random() * tod.length)];
          let pantun = pjr.replace(/pjrx-line/g, "\n");
          conn.sendMessage(id, pantun, MessageType.text, { quoted: m })
        });
    }

  };
//KBBI
  if (text.includes("!kbbi")) {
    const teks = text.replace(/!kbbi /, "")
    axios.get(`https://mhankbarbar.tech/api/kbbi?query=${teks}&apiKey=${apibarbar}`).then((res) => {
      let hasil = `*Resultado* :\n${res.data.result}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//OTHER
  else if (text == '!other') {
    conn.sendMessage(id, `
╔════════════════════╗
║─────〘  *Outros* 〙─────
╠════════════════════╝
║️❖ *!jadwalsholat*
║❖️ *!jadwaltv*
║❖️ *!lirik*
️║❖ *!chord*
║❖️ *!map*
╠════════════════════╗
║───── *${BotName} ──────
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║───── *${BotName}* ─────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//JADWAL SHOLAT
  if (text.includes("!jadwalsholat")) {
    const teks = text.replace(/!jadwalsholat /, "")
    axios.get(`https://mhankbarbar.tech/api/jadwalshalat?daerah=${teks}&apiKey=${apibarbar}`).then((res) => {
      conn.sendMessage(id, '[ 📌 ] Mostrar horários de oração jadwal por favor aguarde...🔎', MessageType.text, { quoted: m })
      let hasil = `Cronograma sholat di ${teks} hari ini adalah\n\n*Imsak* : ${res.data.Imsyak} WIB\n*Alvorecer* : ${res.data.Alvorecer} WIB\n*Dzuhur* : ${res.data.Dzuhur} WIB\n*Ashar* : ${res.data.Ashar} WIB\n*Maghrib* : ${res.data.Maghrib} WIB\n*Isya* : ${res.data.Isya} WIB`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//JADWAL TV
  if (text.includes("!jadwaltv")) {
    const teks = text.replace(/.jadwaltv /, "")
    axios.get(`https://mhankbarbar.tech/api/jdtv?ch=${teks}&apiKey=${apibarbar}`).then((res) => {
      conn.sendMessage(id, '[ 📌 ] Mostrar programação da tv por favor aguarde...🔎', MessageType.text, { quoted: m })
      let hasil = `${res.data.result}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//LIRIK LAGU
  if (text.includes("!lirik")) {
    const teks = text.split("!lirik")[1]
    axios.get(`http://scrap.terhambar.com/lirik?word=${teks}`).then((res) => {
      conn.sendMessage(id, '[ 📌 ] Procurando letras por favor espere...🔎', MessageType.text, { quoted: m })
      let hasil = `Letra da musica ${teks} \n\n\n ${res.data.result.lirik}`
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m })
    })
  }
//CHORD
  if (text.includes("!chord")) {
    const teks = text.replace(/!chord /, "")
    axios.get(`https://arugaz.herokuapp.com/api/chord?q=${teks}`).then((res) => {
      conn.sendMessage(id, '[ 📌 ] Procurando música de acordes aguarde...🔎', MessageType.text, { quoted: m })
      let hasil = `*Titulo* : ${teks}\n*Acorde* : ${res.data.result}`;
      conn.sendMessage(id, hasil, MessageType.text, { quoted: m });
    })
  }
//MAP
  if (text.includes('!map')) {
    var teks = text.replace(/!map /, '')
    axios.get('https://mnazria.herokuapp.com/api/maps?search=' + teks)
      .then((res) => {
        imageToBase64(res.data.gambar)
          .then(
            (ress) => {
              conn.sendMessage(id, '[📌] Procurando por favor aguarde..🔎', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { quoted: m })
            })
      })
  }
//LOGO MAKER
  else if (text == '!maker') {
    conn.sendMessage(id, `
╔════════════════════╗
║────〘  *CRIADOR* 〙─────
╠════════════════════╝
║❖ *!thundername*
║❖ *!sandwrite*
║❖ *!skytext*
║❖ *!blackpink*
╠════════════════════╗
║──── *${BotName}* ────── 
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║  ▌│█║▌║▌║║▌║▌║█│▌▌│█║
║──── *${BotName}* ──────
╠════════════════════╝
╠════════════════════╗
║ _*HALLO I M ${ow}*_
╚════════════════════╝`, MessageType.text, { quoted: m });
  }
//PORNHUB
  if (text.includes('!pornhub')) {
    var porn = text.split("!pornhub ")[1];
    var text1 = porn.split("&")[0];
    var text2 = porn.split("&")[1];
    axios.get(`https://mhankbarbar.tech/api/textpro?theme=pornhub&text1=${text1}&text2=${text2}`).then((res) => {
      imageToBase64(res.data.result)
        .then(
          (ress) => {
            var buf = Buffer.from(ress, 'base64')
            conn.sendMessage(id, 'Espere um minuto...!', MessageType.text, { quoted: m })
            conn.sendMessage(id, buf, MessageType.image, { caption: `Nih tod`, quoted: m });
          })
    })
  }
//LION LOGO
  if (text.includes('!lionlogo')) {
    var porn = text.split("!lionlogo ")[1];
    var text1 = porn.split("&")[0];
    var text2 = porn.split("&")[1];
    axios.get(`https://tobz-api.herokuapp.com/api/textpro?theme=lionlogo&text1=${text1}&text2=${text2}&apikey=${tobzkey}`).then((res) => {
      imageToBase64(res.data.result)
        .then(
          (ress) => {
            var buf = Buffer.from(ress, 'base64')
            conn.sendMessage(id, 'Paciencia todinho..!', MessageType.text, { quoted: m })
            conn.sendMessage(id, buf, MessageType.image, { caption: `Nih tod`, quoted: m });
          })
    })
  }
//NINJA LOGO
  if (text.includes('!ninjalogo')) {
    var porn = text.split("!ninjalogo ")[1];
    var text1 = porn.split("&")[0];
    var text2 = porn.split("&")[1];
    axios.get(`https://tobz-api.herokuapp.com/api/textpro?theme=ninjalogo&text1=${text1}&text2=${text2}&apikey=${tobzkey}`).then((res) => {
      imageToBase64(res.data.result)
        .then(
          (ress) => {
            var buf = Buffer.from(ress, 'base64')
            conn.sendMessage(id, 'Espere um minuto', MessageType.text, { quoted: m })
            conn.sendMessage(id, buf, MessageType.image, { caption: `nih a`, quoted: m });
          })
    })
  }
//JOKER LOGO
  if (text.includes('!jokerlogo')) {
    const teks = text.replace(/!jokerlogo /, "")
    axios.get(`https://tobz-api.herokuapp.com/api/textpro?theme=jokerlogo&text=${teks}&apikey=${tobzkey}`)
      .then((res) => {
        imageToBase64(res.data.result)
          .then(
            (ress) => {
              conn.sendMessage(id, 'Criação de um logotipo coringa', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { caption: `Nihh a`, quoted: m })
            })
      })
  }
//GLITCH LOGO
  if (text.includes('!glitchtext')) {
    var porn = text.split("!glitchtext ")[1];
    var text1 = porn.split("&")[0];
    var text2 = porn.split("&")[1];
    axios.get(`https://tobz-api.herokuapp.com/api/textpro?theme=glitch&text1=${text1}&text2=${text2}&apikey=${tobzkey}`).then((res) => {
      imageToBase64(res.data.result)
        .then(
          (ress) => {
            var buf = Buffer.from(ress, 'base64')
            conn.sendMessage(id, 'Espere um minuto', MessageType.text, { quoted: m })
            conn.sendMessage(id, buf, MessageType.image, { caption: `nih a`, quoted: m });
          })
    })
  }
//WOLF LOGO
  if (text.includes('!wolflogo')) {
    var porn = text.split("!wolflogo ")[1];
    var text1 = porn.split("&")[0];
    var text2 = porn.split("&")[1];
    axios.get(`https://tobz-api.herokuapp.com/api/textpro?theme=wolflogo2&text1=${text1}&text2=${text2}&apikey=${tobzkey}`).then((res) => {
      imageToBase64(res.data.result)
        .then(
          (ress) => {
            var buf = Buffer.from(ress, 'base64')
            conn.sendMessage(id, 'Processando...', MessageType.text, { quoted: m })
            conn.sendMessage(id, buf, MessageType.image, { caption: `Nih a`, quoted: m });
          })
    })
  }
//SNOW LOGO
  if (text.includes('!snowrite')) {
    const teks = text.replace(/!snowrite /, "")
    axios.get(`https://tobz-api.herokuapp.com/api/textpro?theme=snow&text=${teks}&apikey=${tobzkey}`)
      .then((res) => {
        imageToBase64(res.data.result)
          .then(
            (ress) => {
              conn.sendMessage(id, 'espere um minuto', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { caption: `nih a`, quoted: m })
            })
      })
  }
//THUNDER LOGO
  if (text.includes('!thundername')) {
    const teks = text.replace(/!thundername /, "")
    axios.get(`https://arugaz.my.id/api/textpro/thundertext?text=${teks}`)
      .then((res) => {
        imageToBase64(`https://arugaz.my.id/api/textpro/thundertext?text=${teks}`)
          .then(
            (ress) => {
              conn.sendMessage(id, 'espere um minuto', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { caption: `Nih a`, quoted: m })
            })
      })
  }
//BLOOD LOGO
  if (text.includes('!bloodstext')) {
    const teks = text.replace(/!bloodtext /, "")
    axios.get(`https://tobz-api.herokuapp.com/api/textpro?theme=blood&text=${teks}&apikey=${tobzkey}`)
      .then((res) => {
        imageToBase64(res.data.result)
          .then(
            (ress) => {
              conn.sendMessage(id, 'espere bebe', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { caption: `ngeri`, quoted: m })
            })
      })
  }
//WATER
  if (text.includes('!water')) {
    const teks = text.replace(/!water /, "")
    axios.get(`https://tobz-api.herokuapp.com/api/textpro?theme=dropwater&text=${teks}&apikey=${tobzkey}`)
      .then((res) => {
        imageToBase64(res.data.result)
          .then(
            (ress) => {
              conn.sendMessage(id, 'esperar', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { caption: `Nihh a`, quoted: m })
            })
      })
  }
//SAND WRITE
  if (text.includes('!sandwrite')) {
    const teks = text.replace(/!sandwrite /, "")
    axios.get(`https://arugaz.my.id/api/textpro/sandsummer?text=${teks}`)
      .then((res) => {
        imageToBase64(`https://arugaz.my.id/api/textpro/sandsummer?text=${teks}`)
          .then(
            (ress) => {
              conn.sendMessage(id, 'esperar está escrevendo na areia', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { caption: `Nihh a`, quoted: m })
            })
      })
  }
//SKY TEXT
  if (text.includes('!skytext')) {
    const teks = text.replace(/!skytext /, "")
    axios.get(`https://arugaz.my.id/api/textpro/cloudsky?text=${teks}`)
      .then((res) => {
        imageToBase64(`https://arugaz.my.id/api/textpro/cloudsky?text=${teks}`)
          .then(
            (ress) => {
              conn.sendMessage(id, 'Espere ainda...', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { caption: `noh njir`, quoted: m })
            })
      })
  }
//BLEKPING
  if (text.includes('!blackpink')) {
    const teks = text.replace(/!blackpink /, "")
    axios.get(`https://arugaz.my.id/api/textpro/blackpink?text=${teks}`)
      .then((res) => {
        imageToBase64(`https://arugaz.my.id/api/textpro/blackpink?text=${teks}`)
          .then(
            (ress) => {
              conn.sendMessage(id, 'encontrei blackpink', MessageType.text, { quoted: m })
              var buf = Buffer.from(ress, 'base64')
              conn.sendMessage(id, buf, MessageType.image, { caption: `Nih a`, quoted: m })
            })
      })
  }
//OJO DI UBAH
//thanks to
//Deniambrose
//Ramlan Chanel

})
