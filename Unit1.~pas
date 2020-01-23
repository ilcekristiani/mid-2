unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls;

type
  TForm1 = class(TForm)
    Label1: TLabel;
    Label2: TLabel;
    Label3: TLabel;
    Label4: TLabel;
    Label5: TLabel;
    Label6: TLabel;
    Label7: TLabel;
    Edit1: TEdit;
    Button1: TButton;
    procedure Button1Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.dfm}

procedure TForm1.Button1Click(Sender: TObject);
var menu:integer;
begin
  menu:=strtoint(Edit1.Text);
  case menu of 
  1:showMessage('Anda Memilih Menu Nomor '+inttostr(menu));
  2:showMessage('Anda Memilih Menu Nomor '+inttostr(menu));
  3:showMessage('Anda Memilih Menu Nomor '+inttostr(menu));
  4:showMessage('Anda Memilih Menu Nomor '+inttostr(menu));
  5:showMessage('Anda Memilih Menu Nomor '+inttostr(menu));
  else showMessage('Pilih nomor menu 1 sampai 5');
  end;
end;

end.
