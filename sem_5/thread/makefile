WORD Color)
{
    XSetForeground(Disp, GContext, Color);
    XDrawPoint(Disp, Win, GContext, X, Y);
}

void TXWin::DrawLine(int X1, int Y1, int X2, int Y2, DWORD Color)
{
    XSetForeground(Disp, GContext, Color);
    XDrawLine(Disp, Win, GContext, X1, Y1, X2, Y2);
}

void TXWin::DrawRect(int X1, int Y1, int X2, int Y2, DWORD Color)
{
    XSetForeground(Disp, GContext, Color);
    XDrawLine(Disp, Win, GContext, X1, Y1, X1, Y2);
    XDrawLine(Disp, Win, GContext, X1, Y1, X2, Y1);
    XDrawLine(Disp, Win, GContext, X2, Y1, X2, Y2);
    XDraw