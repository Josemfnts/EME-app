# EME Barber Studio — App de Reservas

App de reservas para **EME Barber Studio (EME BS)**. Permite a los clientes reservar cita, ver servicios, equipo y horarios. PWA instalable en móvil con notificaciones push.

## Setup rápido

### 1. Instalar dependencias
```bash
npm install
```

### 2. Configurar variables de entorno
Crea un archivo `.env` en la raíz:
```
VITE_SUPABASE_URL=tu-url-de-supabase
VITE_SUPABASE_ANON_KEY=tu-anon-key-de-supabase
VITE_VAPID_PUBLIC_KEY=tu-vapid-public-key
```

### 3. Desarrollo local
```bash
npm run dev
```

### 4. Desplegar en Vercel
1. Sube este proyecto a GitHub
2. Ve a [vercel.com](https://vercel.com) y conecta tu cuenta de GitHub
3. Importa el repositorio
4. En "Environment Variables" añade:
   - `VITE_SUPABASE_URL` → tu URL de Supabase
   - `VITE_SUPABASE_ANON_KEY` → tu anon key
   - `VITE_VAPID_PUBLIC_KEY` → tu clave VAPID pública
5. Deploy

Vercel te dará una URL tipo `eme-barber-studio.vercel.app`.
