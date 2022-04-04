# tips 
## Linux - Cambiar la configuración del idioma de forma rápida - Español
`$ sudo setxkbmap es  `
## Eliminar carpetas o archivos vacios
`$ find . -type f -empty -delete`

## Formatear USB a valores de fábrica - Windows
### Cuando muestra que el tamaño del Pendrive es mucho menor al que es realmente
`$ diskpart`
`$ list disk`
    
   sirve para listar los discos del equipo
    
`$ select disk [numero de disco a formatear]`
`$ clean`
    
   Para limpiar el disco USB
    
`$ create partition primary`
    
   Esto nos creará la partición primaria
    
- Luego nos dirigimos a  **Administración de discos**
- Y formateamos el disco que queramos
