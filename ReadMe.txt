








##########################################################################
Clip VDO Day12 - Time 1.06
Download AdminLTE 3.2.0
cd NextJS-Workshop
npx create-next-app@latest
√ What is your project named? ... nextjs-wrkshop
√ Would you like to use TypeScript? ... No / Yes
√ Would you like to use ESLint? ... No / Yes
√ Would you like to use Tailwind CSS? ... No / Yes
√ Would you like to use `src/` directory? ... No / Yes
√ Would you like to use App Router? (recommended) ... No / Yes
√ Would you like to customize the default import alias (@/*)? ... No / Yes
cd app
npm i sweetalert2
npm install -g bun
bun upgrade
##########################################################################
Clip VDO Day13 - Time 0.56
Copy Folder dist and plugins of AdminLTE 3.2.0 to Folder Public
copy index.html of AdminLTE to layout.tsx

delete <!DOCTYPE html>
delete <meta charSet="utf-8">
delete <meta name="viewport" content="width=device-width, initial-scale=1">
change text <meta charset="utf-8"> to <meta charSet="utf-8">
find "<img" 16 จุด ในไฟล์ layout.tsx ด้วยการเพิ่ม "/ >"
find "<link" 10 จุด ในไฟล์ layout.tsx ด้วยการเพิ่ม "/ >"
find "<input" 12 จุด ในไฟล์ layout.tsx ด้วยการเพิ่ม "/ >"
delete "<--" 156 จุด ลบคอมเม้นให้หมด
find "class="  ในไฟล์ layout.tsx เปลี่ยนเป็น "className="
style= -> style={{''}}
##########################################################################
Clip VDO Day13 - Time 0.56
Create Repository - Sirichait/tav-next-workshop-2024-web
git status











