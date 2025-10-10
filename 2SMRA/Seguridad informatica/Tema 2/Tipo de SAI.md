*Online*
- Características:
1. Doble conversión de la electricidad
2. Filtra y elimina todo tipo de ruido, fluctuación de tensión
3. La salida de energía es constante
4. Ideales para equipos muy sensibles o de misión crítica.
	1. Servidores
	2. Equipo de telecomunicaciones
	3. Sistemas en centro de datos
![[SAI_OffLine.webp]]
*Offline*
- Función principal:
Mientras la red eléctrica es estable alimenta a los equipos directamente, y solo entra en acción cuando detecta un corte o fluctuación grave. Tampoco filtra el ruido eléctrico
![[Sin título.jpg]]
*Inline*
- Función principal:
- **Modo normal:**
    La energía de la red eléctrica pasa por el SAI, que usa su AVR para estabilizar la tensión y, al mismo tiempo, carga sus baterías.
- **Modo de sobre/subtensión:**
    Si la tensión de la red sube o baja dentro de un rango predefinido, el AVR ajusta la tensión para mantener una salida estable, sin necesidad de usar la batería.
    
- **Modo de corte de energía:**
    Si hay un corte total del suministro, el SAI conmuta instantáneamente a modo de batería para alimentar los equipos conectados
![[Esquema SAI Online.webp]]
Felipe bjkfesn