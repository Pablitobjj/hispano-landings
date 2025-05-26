# HISPAÑO Landing Pages

Landing pages ecosystem for HISPAÑO products deployed on Vercel.

## 🌍 Live Sites

- **Main Landing**: [hispan.io](https://hispan.io)
- **Culture Sight**: [pixel.hispan.io](https://pixel.hispan.io)  
- **Hispanic Premium Network**: [network.hispan.io](https://network.hispan.io)
- **Cultural Brain App**: Redirects to [culturalbrain.net](https://culturalbrain.net)

## 🏗️ Architecture

```
hispan.io → landings/landing_hispano.html
pixel.hispan.io → landings/landing_cb_pixel.html  
network.hispan.io → landings/landing_hispano_pn.html
app.hispan.io → redirect to culturalbrain.net
```

## 🚀 Deployment

Automatically deployed via Vercel when pushing to main branch.

## 📁 Structure

```
hispano-landings/
├── landings/
│   ├── landing_hispano.html      # Main HISPAÑO landing
│   ├── landing_cb_pixel.html     # Culture Sight landing  
│   ├── landing_hispano_pn.html   # HPN landing
│   └── landing_cb_app.html       # CB App landing
├── vercel.json                   # Routing configuration
├── package.json                  # Project metadata
└── README.md                     # This file
```

## 🔧 Local Development

```bash
npm install -g vercel
vercel dev
```

## 🌐 Domain Configuration

Configure these DNS records for your domain:

```
hispan.io              A    76.76.19.61
pixel.hispan.io        A    76.76.19.61  
network.hispan.io      A    76.76.19.61
app.hispan.io          A    76.76.19.61
```

## 🔗 Related Links

- **Cultural Brain Platform**: [culturalbrain.net](https://culturalbrain.net)
- **Documentation**: [developers.hispano.io](https://developers.hispano.io)
- **Company**: [HISPAÑO](https://hispan.io)

---

**Powered by HISPAÑO - The Hispanic Digital Intelligence Infrastructure**
